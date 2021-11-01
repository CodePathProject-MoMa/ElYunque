# ElYunque
An app that classifies any image of fauna and flora! 

Unit 8: Group Milestone - El Yunque README 
===

## Table of Contents
1. [Overview](#Overview)
1. [Product Spec](#Product-Spec)
1. [Wireframes](#Wireframes)

## Overview
### Description
Inspired by a jungle trek in Peru, El Yunque is named after the only rainforest in the United States! This app will let you take a picture of flora and fauna in an area and classify it for you using machine learning! You can drop a pin so that others can go and check out the flora as well! You can share your picture with freinds afterwards. 


### App Evaluation
- **Category:** Photography / Nature 
- **Mobile:** This app would primarily be used on mobile because ideally it would be used by someone hiking in a rainforest, or an unfamiliar area, and they would like a quick way to identify a plant. By dropping a pin of the types of plants in the area, you can build a visual "database" of plants within an area, and allow others to do research, cluster plant spieces, or just enjoy the plant! Later on, a UI can be built out for the front end for easy insight and access to the data. Social interactions can also be added, by letting users share thier favorite plants on a timeline or a newsfeed!
- **Story:** When a user comes across a plant species they wish to identify, they open the app, and take a picture. After taking the picture, they can identify where they found this plant, and if they want to share it on thier feed. If they dont want to take any pictures, they can just scroll thier feed, or look on the map to see all the different types of flora in the area. 
- **Market:** Any individual, researcher, scientist, hiker, plant enthusiast 
- **Habit:** More likely to be used when a user is on a hike, on a trip/vacation, planning for a trip, or planning to go research plants in a specific area. 
- **Scope:** Start with the camera and classifier identifying plants whenever an image is captured. After this is built out, we can create the map with the ability to drop and share with friends. Then create the home page where you can see the most recent classifications made. Can build this out to include many different plant and flower datasets all over the world. 


## Product Spec
### 1. User Stories (Required and Optional)

**Required Must-have Stories**

* User logs in to access home page feed, recent finds across the world, with a banner at the bottom allowing them to choose what to do next (similar to instagram)
* User clicks on the camera to upload a picture, or select from thier camera roll (similar to instagram)
* After they identify the image they would like to choose, the ML model classifies the plant species. 
* They then have an option to use location settings to drop a pin on a map (maybe google maps?) 
* Also have an option to share it with friends
* Profile pages for each user
* Settings (Accesibility, Notification, General, etc.)

**Optional Nice-to-have Stories**

* Connect with others who have classified the same plant in the area to see what other plants they've seen or studied 
* Create a web app for easy discovery of plants in an area. 
* Page for most popular plant classifed 
* Screen that uses NLP on the plant description to pull recent and relevant research papers on the plant species 


### 2. Screen Archetypes

* Login 
* Register - User signs up or logs into their account
   * Upon Download/Reopening of the application, the user is prompted to log in to gain access to their profile information 
   * After logging in, the landing screen will be the home feed 
* Landing screen - think instagram for plant species research 
* Camera Screen - Capture image of plant species to be identified 
   * User also has the option to select an image from thier camera roll
* Classifed Image Return Screen
   * The classified image match gets returned, as well as a description of the plant species. 
* Map screen
   * Allows user to drop a pin where they found the plant species, or get to this screen using navigation. 
   * Have a button to share (to landing screen)
* Settings Screen
   * Lets people change language, share, and app notification settings.

### 3. Navigation

**Tab Navigation** (Tab to Screen)

* Landing Screen 
* Camera 
* Map
* Settings

Optional:
* Discover (Top captured plant species worldwide) 
* Screen that links to research articles relevant to the plant using NLP 

**Flow Navigation** (Screen to Screen)
* Forced Log-in -> Account creation if no log in is available
* Home screen -> infinite scroll -> click on user profile 
* Camera -> Take picture
* Camera -> Choose from camera roll -> allow access? -> View camera roll -> select image 
* Select photo -> Description of classified plant is returned - Option 1: Share your image to home screen with a caption
* Select photo -> Description of classified plant is returned - Option 2: Drop a pin on a map -> view map 
* Settings -> Toggle settings

## Wireframes
<img src="![](https://i.imgur.com/01PpAxd.jpg)" width=800><br>
