---
layout: layouts/base.njk
title: Levent Ali - Group Engineering Manager
description: Levent Ali is an experienced leader with over a decade delivering internet products and building cross-functional teams."
---

# I'm Levent Ali.

## Group Engineering Manager at [Intercom](https://www.intercom.com/).

I'm a technology leader with almost two decades experience delivering internet products and building highly productive, engaged, cross-functional teams.

I love making the complicated simple by getting talented people together and getting out of their way.

At Intercom a few of the areas where I've had impact:

* Helping establish the London R&D office 
* Setting up our first chat bot focussed product team
* Establishing and leading the automated support group
* Improving our engineer onboarding process
* Hiring product managers, directors, and engineers
* Shipping strategic cross org projects, without burnout and on time

My teams look after our self-serve solutions, including our [Resolution Bot](https://www.intercom.com/automated-answers), [Custom Bots](https://www.intercom.com/customizable-bots) and [Help Center Articles](https://www.intercom.com/articles) products.

I have previously worked with [Xively](https://xively.com/), [Goodlord](https://www.goodlord.co/), [Osper](https://osper.com/), [LogMeIn](https://secure.logmein.com/home/en) and [Umbrellium](http://umbrellium.co.uk/).

You can find me on [Twitter](https://twitter.com/lebreeze), [Instagram](https://www.instagram.com/lebreeze), [GitHub](https://github.com/levent) and [LinkedIn](https://www.linkedin.com/in/leventali/).

I write and maintain [Suite](https://suite.leventali.com/about), which is a set of personal tools I use for tracking moods and tasks.

{% if collections.posts %}
## Incomplete thoughts
{% endif %}
{% for post in collections.posts %}
* [{{ post.data.title }}]({{ post.url }})
{% endfor %}


[About me](/about/)
