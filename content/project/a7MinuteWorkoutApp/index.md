---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "7 Minute Workout App"
summary: "The Android app developed with Kotlin will walk through the user to finish a 7-minute workout with 12 different mini workouts."
authors: []
tags: [Android]
categories: []
date: 2020-07-29T14:55:53-07:00

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



I designed and developed a 7-minute workout Android app that encompasses 12 different workouts. Each workout will last 30 seconds. Between workouts, users have 10 seconds to rest. The basic features of the app include displaying images for workout, counting down workout and rest time, using rings and speaking out workout names to enable eyes-free and hands-free workout experience, showing the number of workout the user currently is on, etc. Beyond those basic features, I also incorporate a BMI calculator into the project which will take users input of height and weight in either US or metric units, and output the BMI value and relevant recommendations. The workout history is available for users to check out, and they are stored with Sqlite batabase.

{{< youtube wQaUi4u6lj0>}}

In the exercise view, the timer will count down rest time or workout time, displaying the remaing time in a round progress bar. The picture and name of the workout will be displayed during workout. Auditory remainder of workout name and end of workout will be supported. During workout, user can return to main page by clicking the back button. Before directing the user, I designed a pop-up dialog the requires confirmation from user again  in case the user touches the button accidentally during the workout.



{{< youtube ioRrD5StHpg>}}

The addon features, including calculating BMI and displaying workout history, are integrated in the App. BMI calculator accepts both US and metric unit to take user input. I enable this function by creating customed RadioGroups with customed RadioButtons. The history workout date and time are stored in Sqlite database and displayed with customed RecyclerView. To exit BMI or History views, I deployed toolbar to access main screen.

{{< youtube AQS_5dSCM68>}}

The current progress of workout is indicated in the bottom of the page with current workout number. The current workout is marked white, the finished workout is marked green and unfinished is marked grey. This function is achieved by a customed RecyclerView. At the end of the workout, the user is directed to a finish page and they can come back to the main memu from there.









































































