---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Happy Places"
summary: "An android app that allows users to store descriptive and locational information to their favorite photos."
authors: []
tags: ["Android"]
categories: []
date: 2020-08-08T14:11:19-07:00

# Optional external URL for project (replaces project detail page).
external_link: ""

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: false

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



Happy Places is an Android application designed for storing the locational information for a user's most important pictures. The basic features of the app include:

- Master/detail view of each photo.
- Right swipe to edit and left swipe to delete photo entry in master view.
- Detail view of photo entry which contains title, description, date, location of the image.
- Edit view of photo entry to enter various information.
- Location could be entered through google places/maps or selected based on device's GPS information.
- Location detail view to display the selected location onto Google Maps.

It integrates the location information with device's GPS and Google Places/Maps API. The data is stored into the local device via SQLite database.

{{< youtube zfXi93L_dKU>}}



