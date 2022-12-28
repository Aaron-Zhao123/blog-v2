---
layout: page
permalink: /random/
title: Random
description:
nav: true
nav_order: 5
---

## Github overview

{% if site.data.repositories.github_users %}
<div class="repositories d-flex flex-wrap flex-md-row flex-column justify-content-between align-items-center">
  {% for user in site.data.repositories.github_users %}
    {% include repository/repo_user.html username=user %}
  {% endfor %}
</div>
{% endif %}

---

## Some Coding Projects 


{% if site.data.repositories.github_repos %}
<div class="repositories d-flex flex-wrap flex-md-row flex-column justify-content-between align-items-center">
  {% for repo in site.data.repositories.github_repos %}
    {% include repository/repo.html repository=repo %}
  {% endfor %}
</div>
{% endif %}

---

## Other interests

<div class="row mt-4">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/bjj.jpg" class="img-fluid rounded z-depth-1" zoomable=true%}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/bike2.png" class="img-fluid rounded z-depth-1" zoomable=true%}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/bike3.jpeg" class="img-fluid rounded z-depth-1" zoomable=true%}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/coffee.JPG" class="img-fluid rounded z-depth-1" zoomable=true%}
    </div>
</div>

I enjoy practicing material arts. I used to compete in amature kickboxing and now I am a 2nd degree blue belt in Brazilian Jiu Jitsu. I train at [CDBJJ](https://cdbjj.com/) under Jerry Sonenarong when I am in China, and [BTT Cambridge](https://www.bttcambridge.com/) under Leo Gamarra when I am in the UK (picture 1 is me doing BJJ).

I am a recreational bike rider, I own a [Brompton folding bike](https://www.brompton.com/) (pic 2) and a [Specialized road bike](https://www.specialized.com/gb/en) (pic 3), both bought second-hand and with [Brooks saddles](https://www.brooksengland.com/en_uk/).

I am a coffeehead and use the following setups (pic 4):

* [La Pavoni Professional Lusso](https://www.lapavoni.com/en/product/professional-lusso/) (inspired by [George](https://cas.ee.ic.ac.uk/people/gac1/))

* [Niche Zero Grinder](https://www.nichecoffee.co.uk/products/niche-zero)

* [Decent DE1PRO](https://decentespresso.com/overview)
