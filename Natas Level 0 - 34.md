
## Introduction

So, first off **what is Natas?**

Natas is a series of web-based challenges from the folks at OverTheWire. It teaches different web-security concepts in all of its 34 Levels. Each challenge is hosted on its own website using the format http://natasX.natas.labs.overthewire.org

The goal is to find the password and keep on moving up through the challenges till the end. With the password for the next level hidden somewhere within the webpage. You can check out more about these challenges and others by visiting their home page: https://overthewire.org/wargames/

----

### Natas Level 0 | Inspecting the Site

First, we head over to the natas0 site ([http://natas0.natas.labs.overthewire.org/](http://natas0.natas.labs.overthewire.org/)) and log in with the username: natas0 and the password natas0

![[natas0-1.png]]

We are then greeted with a message stating that we can find the password for level 1 somewhere on this page.

![[natas0-2.png]]

Naturally the first step in all web-based challenges and CTFs is to inspect the code of the site to see if we can get an idea of what is going on with the page. Which can be done by right clicking and either clicking View page source or Inspect

![[natas0-3.png]]

This brings up the source code of what is currently running on the page, we expand the `<div>` tags and see the password for level 1.

![[natas0-4.png]]

----

