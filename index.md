---
---

<!-- 
    To do list
    1.  


  _include/feature.html: 
    How is this different from figure.html, and col.html ? 
-->

# Introduction

 Nima Tree Services is a small family owned company offering tree care services in the Greater Toronto Area.  

{% include section.html %}

## Past Work

<!------------------------->
<!--  ADD Past projects  -->
<!------------------------->

{% capture text %}

Check out the images from our past tree work undertaken.

{%
  include button.html
  link="projects"
  text="Browse our projects"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/imageoftree.jpg"
  link="projects"
  title="Our Projects"
  flip=true
  style="bare"
  text=text
%}


<!----------------------->
<!--  SERVICES OFFERED -->
<!----------------------->

## Services Offered
The following tree care services are offered: 

- Pruning - Even though early spring, later fall and winter are generally considered to be ideal for pruning jobs, we offer our services year around. 
- Trimming
- Removals
- Hedging 


<!--{%
  include button.html
  link="research"
  text="List of Services"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}
-->


## Liability and Insurance

Our company offers 2 Million dollars in Commercial Liability (CBL) in case of any damage to you property. 


## Team

Sangay is the owner and also the lead tree climber. He has years of experience and knowledge in the tree care industry. Sangay is awaiting to be certified as a Specialist Tree Climber with with International Society of Arboriculture (ISA). He is also working towards his dream of becoming a ISA Certified Arborist. 

## Service Areas

We offer our services to most areas in the Greate Toronto Area (GTA). 


## Call for a Quote 
All our quotes are free! So don't hesitate to call for any tree realted inquires. 

<!------------------------->
<!--      END            -->
<!------------------------->














{% capture text %}

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.

{%
  include button.html
  link="research"
  text="See our publications"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

<!--{%
  include feature.html
  image="images/imageoftree.jpg"
  link="research"
  title="Our Research"
  text=text
%}
-->


{% capture text %}

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.

{%
  include button.html
  link="team"
  text="Meet our team"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

<!--{%
  include feature.html
  image="images/photo.jpg"
  link="team"
  title="Our Team"
  text=text
%}
-->
