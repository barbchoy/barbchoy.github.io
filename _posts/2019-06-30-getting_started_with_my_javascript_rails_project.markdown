---
layout: post
title:      "Getting Started with my JavaScript Rails Project"
date:       2019-06-30 12:35:37 -0400
permalink:  getting_started_with_my_javascript_rails_project
---


When I first started this JavaScript Rails project, I thought "I don't want to break my rails project." I was proud of my rails project. I did a Airbnb like application. The models are houses, users that can be owners or renter, stays and reviews. Users are connected to houses via stay. After the stay, users have an option to give reviews and reviews belong to both houses and users. It was working very well. Why would I want to break my project?

I started off my looking at some videos that my project lead sent me. It leads me to first render with my index page - the house index page. The house index page lists all houses that are available for rent. First I started by adding a serializer for the house model. Next I modified the house_controller.rb to handle json. Then I created house.js to write a few functions to send AJAX request to the server, get the response and attach it to the element in the DOM, without having to reload the whole page. The page looks great and it is fast when I click the button to see more details of each item on the index page.

I have a new form in my rails project. I wrote some functions to hijack the submisson of the new form, and saved the submission through AJAX and display the results through jQuery again. 

After a while I started the appreciate the beauty of using JavaScript on my Rails project. My app loads much faster, and with all the debugging tools that come with Chrome the project is actually not too bad. Here are some advice that I would give to someone about to start the project. 1) Make sure your jQuery is installed and loaded by adding the gem in the gemfile. It caused me much pain in the beginning when nothing was working. 2) Make use of the videos a lot. When I didn't have a clue where to start, I was using the videos as a code along. 3) Go back to the lessons and labs. They usually provide some simple example in a way that is easy to understand. 4) Use the internet. It is amazing how much we can find nowadays in Stackoverflow, YouTube etc. 

Good luck with the project!






