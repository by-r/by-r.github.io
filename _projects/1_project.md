---
layout: page
title: Tempah Kereta
description: Internal tool for staff to book vehicles.
img: assets/img/12.png
importance: 1
category: work
related_publications: false
---

Fullstack app built primarily using Django with Bootstrap.
Might write a blog post someday on the process of building this app.

Went thru a lot of trial and errors, learnt a lot of things. Certainly, one of my favorite project so far.

```bash
mkdir tempahKereta && cd tempahKereta    
pip install django 
django-admin startproject tempahKereta .
```

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/1.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/3.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/5.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    On the left, main calendar menu. Middle, booking form. Right, .
</div>
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/12.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Landing Page.
</div>

**Main Features**:
- Easily book vehicles no matter the location.
- Realtime update on booking status.
- Interactive Calendar.

<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/6.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/11.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    You can also have artistically styled 2/3 + 1/3 images, like these.
</div>

Primarily built this tool/app to ease booking process. Anytime, anywhere, as long as you have internet access.


**What I learnt**:

Learnt a lot valuable knowledge that can be implemented in my future projects (and also my old abandoned projects).
Notable points:
1. The importance of virtual environments : Isolating/Containerizing apps would ease the development process in the long run. Makes running locally and deploying a lot more easier.
2. Keeping Secret Keys : Importing secret keys (API keys, Django keys, etc..) is a lot more safer rather than just importing it there, cause it leads the app to be vulnerable to attacks (?) and whatnot
3. Implementing JS scripts/libraries to HTML files : Using external libraries to implement functions that are already built instead of building it by myself.
4. Understanding JSON : Studying/Researching the importance of JSONresponse or calling APIs to the frontend to display proper info.
5. Understanding Django ORM : WIP