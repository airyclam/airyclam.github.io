---
layout: essay
type: essay
title: "Final Project Idea"
date: 2020-11-01
labels:
  - Software Engineering
  - Meteor
---
## Overview
Although there's a wide range of information on COVID-19 available on the internet, it can be hard to find exactly what you need. There's currently no easy way to find the most up-to-date and accurate information about COVID-19 for Hawaii residents and visitors. Even within just government-sponsored websites like [https://hawaiicovid19.com/](https://hawaiicovid19.com/) and [https://health.hawaii.gov/coronavirusdisease2019/](https://health.hawaii.gov/coronavirusdisease2019/), there's just too much to look through. The call centers available are currently overloaded with people asking questions like "Where is the nearest testing center?" or "What do I do if my family member tested positive?"

The goal of this project is to provide a one-stop-shop for COVID-19 information related to Hawaii. Besides the chatbot itself which is going to use the Dialogflow Google Cloud Service, we plan to implement two other pages accessible to the admin that allow for easy maintenance of this bot.

1. An "Add Intents" page where the admin can fill out a form with fields like "Intent Name", "Training Phrases", and "End Response".

2. A "View Intents" page where the admin can view all intents currently supported by the bot. On this page they can also select an "edit" button which brings them to a form where they can edit the different fields, and a "delete" button where they can delete the selected intent.


## Use case ideas
- User goes on the landing page and sees the chatbot tab and can immediately start talking with the chatbot to get information about Covid-19 such as testing centers, symptoms of Covid-19, traveling out of state, etc.

- Admin can manage the chatbot by adding more intents, which are phrases that the chatbot can say as a response to user input.

- Admin can also edit and delete any intents.

## Beyond the basics
After implementing and integrating the chatbot to our website, here are some advanced features that could be in scope of the project:
- Have a statistic tab for admins to see which intent has been encountered the most. It will show a chart (pi chart) which shows the frequency of intents across all user sessions with the chatbot. This helps the admin see which type of information about Covid-19 do people seek out the most.

- Allow the user to review how the session went and report any problems. These results would be displayed in the admin's statistics page.

This essay was collaboratively written by Eric Lam, Irene Ma, Shane Severino, and Alyssandra Cabading.
