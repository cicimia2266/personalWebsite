---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Planit"
summary: "Planit allows users to plan and manage projects together across multilpe Android devices on its minimalist interface."
authors: []
tags: ["Android"]
categories: []
date: 2020-08-08T14:12:42-07:00

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



Planit is a project management Android application I designed that enables multiple users to collaborate and plan together. The basic features include:

- User authentication and authorization, including signing in, signing up and signing out.
- CRUD of user profile.
- Creating task boards, inviting members to join the board, and deleting task boards.
- Creating, updating and deleting task lists inside task boards.
- Creating and deleting task cards inside task lists in master card view, and displaying tag color and selected collaborators for each card.
- Updating and deleting task card detail view with the capability to add tag color, assign collaborator, and choose due date.
- Dragging and dropping the cards to change card position inside a task list.

<br>

Please check out the features and interfaces of the project.

{{< youtube mwstgfazDzU>}}

<br>

<br>

User authentication process is introduced in the video below.

{{< youtube dHkfSTl5Kqg>}}

<br>

<br>

Specifically, I used Firebase for authentication process, cloud Firestore database, and cloud storage to store user-generated contents.



{{< gallery album="gallery" >}}