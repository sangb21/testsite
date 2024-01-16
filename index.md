---
---

<!-- 
    To do list
    1.  


  _include/feature.html: 
    How is this different from figure.html, and col.html ? 
-->

# Introduction



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

{%
  include button.html
  link="research"
  text="List of Services"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}


## Liability and Insurance

Our company offers 2 Million dollars in Commercial Liability (CBL) in case of any damage to you property. 


## Team

Sangay is the owner and also the lead tree climber with years of experience and knowledge in the tree care industry. Sangay is awaiting for his certification as a Specialist Tree Climber Certification with International Society of Arboriculture (ISA), and also working towards his dream of becoming a ISA Certified Arborist. 


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
