---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Photo Donut"
summary: "Photo Donut is a social-focused photo-sharing application implemented with Django and python. It's a full-stack application that focused on both back-end application business logic and data handling, and front-end user interface."
authors: []
tags: [Web]
categories: []
date: 2020-07-30T10:15:45-07:00

# Optional external URL for project (replaces project detail page).
external_link: ""

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: true

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
---



Designed and implemented a mini social-focused full stack django photo-sharing web application.

\- The overall functionality of this full stack web application includes: authentication, authorization, follow/unfollow user, making posts, master/detail view of posts, etc.

\- Designed and implemented the front end interface using html, bootstrap, javascript, allowing user to interact with the application for all mentioned modules.

\- Designed and implemented the database + wrapper layer using django model, to support application’s business logic.

\- Implemented django views to handle different web requests using python. Added logs and proper unit tests for these views as well.

\- Deployed the web application to Heroku to enable public access.



{{< figure src="donut1.png" title="Explore world function in PhotoDonut" >}}

The explorer view allows users to explore photos from around the world. The photos are displayed in this compact view designed with html/css, bootstrap and javascript.



{{< figure src="donut2.png" title="Home page in PhotoDonut with comments and likes" >}}

Master post page allows users to browse the photos published by their chosen/followed users. They are able interact with photo publishers by commenting and liking the photos.



{{< figure src="donut3.png" title="Add a new post in PhotoDonut" >}}

New photo can be published with customized description.



{{< figure src="donut4.png" title="Profile page in PhotoDonut" >}}

Profile page will display all the photos published by the current user. It will also summarize the total count of post, followers and following accounts.



{{< figure src="donut5.png" title="Detail post in PhotoDonut with comments and likes" >}}

By clicking on on specific photo, users could access the detail post page where likes and comments are displayed on the right hand side.



{{< figure src="donut6.png" title="Explore others profile page to follow or unfollow in PhotoDonut" >}}

Another user's profile page could be accessed by clicking through its profile picture. The the current user could choose to follow or unfollow him/her.



{{< figure src="donut7.png" title="change profile picture or user name in PhotoDonut" >}}

The profile picture and username could also be changed.



{{< figure src="donut8.png" title="Log in page in PhotoDonut" >}}

In order to access the website, the user needs to log in first with a username and password.



{{< figure src="donut9.png" title="Sign up page in PhotoDonut" >}}

If not registered, the website will allow user to sign up with username, email address, profile picture and password.

<br>

<br>

The website could be accessed:

https://pure-caverns-18927.herokuapp.com/auth/signup

The code could be accessed:

https://github.com/cicimia2266/instaDemo



