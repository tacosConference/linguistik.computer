---
layout: misc
title: Archiv
---

## Statistik

Folgende Unis haben die TaCoS am häufigsten ausgerichtet:

{% comment %}
So, this code below is rather ugly. We first go through all conferences and group them by location. This yields an array that looks like this
(not valid Liquid code, but you get the idea):

[
    {name => "Heidelberg", items => [tacos_1, tacos_2, tacos_3]},
    {name => "Bochum", items => [tacos_1]},
    ...
]

Every entry in this array is a group, which as a name (the location), and the items (all conferences at this location).

We loop through the array again, and group all the groups by the size of items array, i.e., by the number of conferences at that location.

This creates an array like this:

[
    {name => 3, items => [
        {name => "Heidelberg", items => [tacos_1, tacos_2, tacos_3]},
        {name => "Saarbrücken", items => [tacos_1, tacos_2, tacos_3]},
    ]},
    {name => 1, items => [
        {name => "Bochum", items => [tacos_1]},
        {name => "Leeuwarden", items => [tacos_1]},
    ]}
]

Now, the "name" of the group is the number of conferences its items all have, and the items are locations together with the exact conferences held there.

We sort this by the "name" property, i.e., the number of conferences held there; descendingly, by reversing.

References:

- https://shopify.github.io/liquid/
- https://jekyllrb.com/docs/liquid/filters/

{% endcomment %}

{% assign groups = site.data.conferences | group_by: "location" | group_by_exp: "group", "group.items | size" | sort: "name" | reverse %}

{% for group in groups %}
- {{ group.name }}× {{ group.items | sort: "name" | map: "name" | join: ", " }}
{% endfor %}

(enthält die TaCoS 2020 in Heidelberg, die damals pandemiebedingt abgesagt wurde)

## Liste aller Tagungen

_Tipp: Der Link `linguistik.computer/<Jahr>` (z.B. [linguistik.computer/2023](https://linguistik.computer/2023)) führt immer zur jeweiligen Tagungswebsite, selbst wenn die finale Website eine andere ist._

{% for conference in site.data.conferences %}

<h3 id="{{ conference.name | slugify }}">{{ conference.edition }}. {{ conference.name }}, {{ conference.location }}</h3>

<ul class="fa-ul">
    {% if conference.date %}<li><span class="fa-li"><i class="fa-regular fa-calendar-days" aria-hidden="true"></i></span><em>{{ conference.date }}</em></li>{% endif %}
    {% if conference.venue %}<li><span class="fa-li"><i class="fa-solid fa-location-dot" aria-hidden="true"></i></span>{{ conference.venue }}</li>{% endif %}
    {% if conference.url %}<li><span class="fa-li"><i class="fa-solid fa-globe" aria-hidden="true"></i></span><a href="{{ conference.url }}" target="_blank">Website</a></li>{% endif %}
</ul>

{% endfor %}
