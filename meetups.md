---
title: Meetups
nav: meetups
permalink: /meetups/
lead: The Elon meetup in Prague is a regular get-together of EV owners and fans. Anyone is welcome, with or without a car.
description: Elon meetup Prague at Hotel Čertousy, e-SALON, ElektroFest and other Elon Club events.
---
{% include rel.html %}

## Elon meetup Prague

We meet on a weekday evening, usually Wednesday from 18:00, at [Hotel Čertousy](https://www.google.com/maps/search/?api=1&query=Hotel+%C4%8Certousy+Praha) in Prague. Just type "Hotel Čertousy Praha" into your navigation. Parking and charging are available on site.

What a meetup usually looks like:

- talk about EV topics and real-world experience,
- accessories for electric cars,
- updates from the Cybertruckin.EU project,
- Elon Club t-shirts and merchandise to order,
- a light show in the car park,
- good company and a relaxed evening.

The next date and sign-up are always announced in the [WhatsApp group]({{ site.cta.url }}) and in [News]({{ rel }}news/). Ideas for other events are welcome at [srazy@elonclub.cz](mailto:srazy@elonclub.cz).

Passing through Prague in your EV? Come and say hello. We speak Czech, Slovak and English.

<a class="btn" href="{{ site.cta.url }}">Join the WhatsApp group</a>

## Where else to find us

Besides the Prague meetups we have a stand at the **e-SALON** electric mobility show in Prague Letňany and we go to **ElektroFest** in Pelhřimov. In November 2023 we watched the Starship launch together.

## Past meetups and events

{% assign events = site.posts | where_exp: "p", "p.categories contains 'meetups'" %}
<ul>
{% for p in events %}
<li><a href="{{ rel }}{{ p.url | remove_first: '/' }}">{{ p.title }}</a> ({{ p.date | date: site.t.date_format }})</li>
{% endfor %}
</ul>

Older events without their own page yet:

- 28 June 2023 Elon meetup Prague, Hotel Čertousy
- 9 to 10 June 2023 ElektroFest Pelhřimov (Eco Rally, test drives, light show)
- 31 May 2023 Elon meetup Prague, Hotel Čertousy
- 20 April 2023 Starship launch watch party in a Prague restaurant
- 25 January 2023 Elon meetup Prague
- 26 January 2022 Tesla meetup Prague
