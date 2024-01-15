---
title: Contact
nav:
  order: 5
  tooltip: Email, address, and location
---

<!-- 
- _include/section.html
- _inlude/button.html: Create clickable links for email, phone numbers, etc. - referred to as buttons.
- _include/cols.html: split the page or section of page into multiple columns
- _include/figure.html: Add a figure, add caption

-->

# Contact Us

Viewmount Avenue,

Toronto, ON

Canada



{%
  include button.html
  type="email"
  text="info.trees123@.gmail.com"
  link="info.trees123@gmail.com"
%}
{%
  include button.html
  type="phone"
  text="(647) 868-5744"
  link="+1-647-868-5744"
%}
{%
  include button.html
  type="address"
  tooltip="Our location on Google Maps for easy navigation"
  link="https://www.google.com/maps"
%}

<!--{% include section.html %}-->

{% capture col1 %}

{%
  include figure.html
  image="images/imageoftree.jpg"
  caption="Service Area"
%}

{% endcapture %}

{% capture col2 %}

{%
  include figure.html
  image="images/imageoftree.jpg"
  caption="Image of a tree"
%}

{% endcapture %}

<!-- TO ADD COLUMNS USE cols.html file -->
{% include cols.html col1=col1 col2=col2 %}

<!--{% include section.html dark=true %}-->

{% capture col1 %}
Lorem ipsum dolor sit amet  
consectetur adipiscing elit  
sed do eiusmod tempor
{% endcapture %}

{% capture col2 %}
Lorem ipsum dolor sit amet  
consectetur adipiscing elit  
sed do eiusmod tempor
{% endcapture %}

{% capture col3 %}
Lorem ipsum dolor sit amet  
consectetur adipiscing elit  
sed do eiusmod tempor
{% endcapture %}

<!--{% include cols.html col1=col1 col2=col2 col3=col3 %}-->



