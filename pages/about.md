---
title: About
layout: about
permalink: /about.html
---
{% include feature/jumbotron.html %} 

{% include feature/nav-menu.html sections="About the Collection;Learn More" %} 

## About the Collection

The year 2020 marks the 100th anniversary of the passage of the 19th Amendment, guaranteeing and protecting women's constitutional right to vote. Despite decades of marches, petitions, and passage of the 19th Amendment, it did not grant voting rights for all. The ongoing fight for equity continues today.

“She Changed the World: NC Women Breaking Barriers,” an initiative by the North Carolina Department of Natural and Cultural Resources, celebrates the achievements of North Carolina women and explores the diversity of their experiences and impact on our history.

{% include feature/item-figure.html objectid="coll038" width="50" %}

<div class="row">
<div class="col-md-6">
{% include feature/item-figure.html objectid="coll055" width="100" caption="I'm creating a custom caption for this image, and I've made the image to the right have no caption by giving its caption a value of false." %}
</div>
<div class="col-md-6">
{% include feature/item-figure.html objectid="coll058" width="100" caption=false %}
</div>
</div>

## Learn More

Visit the full [North Carolina Digital Collection](https://digital.ncdcr.gov) to learn more. 

We invite you to join us by sharing your story with #SheChangedtheWorld and #NCHerstory.

{% include feature/card.html objectid="coll053" header="Here is a card header!" title="A title for my card" text="Some information about this item" width="50" centered="true" %}

### Here's a pdf to read!

{% include feature/item-pdf-embed.html objectid="coll015" width="50" %}

### Embedding a video

If I had a video I would embed it this way:

`{% raw %}{% include feature/item-video-embed.html objectid="demo_004" %}{% endraw %}`

### Buttons, alerts, and modals

{% include feature/button.html text="This button links somewhere!" link="https://collectionbuilder.github.io/" color="success" centered="true" %}

{% include feature/alert.html text="This is an *alert* that 'warns' a user with centrally aligned text." color="warning" align="center"  %}

{% include feature/modal.html button="This is a modal using a 'primary' colored button to invite clicking" title="When clicked:" text="A Modal will pop out a box with some more information" color="primary"  %}



<div class="clearfix"></div>

