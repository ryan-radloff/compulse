# Check-Up (TAMUHack 2022)  
# Purpose
## About
Did you remember to turn the oven off? Was the curling iron unplugged when you left this morning? Is your car locked? People with anxiety and Obsessive Compulsive Disorder (OCD) struggle to remove these thoughts without repetitively checking first. Compulsive checking actions distract from daily routine and are exhausting to keep up with. Studies on OCD conclude that compulsive checking can worsen intrusive thoughts.

Check-Up is a mobile application which aims to relieve these intrusive thoughts and actions through providing a centralized checklist. Check-Up allows a user to create a customized task list based on their intrusive thoughts.

Rather than wasting the time to check a car lock multiple times, a user can mark the task as complete in the app and upload photo evidence. If they feel unsure about whether the task was completed later in the day, they can check the app to relieve worry.

## Inspiration
Our developer team was inspired to create this app based on our personal struggles with mental health. All of our developers have or are close to someone with anxiety or OCD. Intrusive thoughts and compulsive checking, symptoms of anxiety and OCD, distract from everyday tasks like learning, sleeping, and eating. “It can be incredibly frustrating,” says one of our developers, professionally diagnosed with OCD, “to have to get out of bed in the middle of the night just to check if I locked my door.” “I have to stop on my way to class multiple times to check if I have my laptop charger in my backpack,” says another developer who was diagnosed with generalized anxiety. “I have my phone in my hand the whole time, it would be much easier to check something already in my hand instead of stopping to unzip my backpack, verifying the charger is in my bag and then zipping it back up”

We know it’s not only the developers who struggle with intrusive thoughts. Adults and college students are negatively affected. With the COVID-19 pandemic, anxiety rates in young adults and students are at an all time high. Active Minds states 91% of surveyed college students report stress or anxiety as the most common ways that COVID-19 has impacted their lives. Additionally, the Anxiety & Depression Association of America reports that OCD affects 2.2 million adults in the U.S.

With Check-Up, we aim to relieve the stress of students like us. Mental illness doesn’t go away, we learn how to work with it. Our goal is to use Check-Up as an efficient method to calm intrusive thoughts. As a bonus, Check-Up uses healthy strategies for personal growth in subduing compulsive checking.

We believe that Check-Up is a real solution to real problems we face and are excited to make a positive impact on a community we’re a part of.

# App Design
## Unique Features
Check-Up is no ordinary productivity or checklist app. It is designed to promote positive change in personal mental health. Here are noteworthy features of the app.

### Video Evidence
Check-Up allows a user to submit video evidence of their task completion. The feature further helps the user have a “peace of mind” about tasks they worry are completed.
### Automatic Time Zone Sync
When a task is marked as complete, the time completed is recorded. The app automatically syncs across time zones with DateTime class.
### Integrated WebAPI
A microservice is deployed on Google Cloud which serves as an interface between the app and the relational Cloud SQL database. Because of this, the data is easily accessible from any platform.
### Drag and Drop Ease
A user can easily reorganize and prioritize tasks by dragging and dropping them on the task list
### “Dark mode” Style Interface
Most intrusive thoughts occur at night when a person is most likely to be tired. Therefore, the app is visually designed for low-light environments to be easy-on-the-eyes at night.
### Cross-Platform Compatibility
The app is compatible with iOS and Android phones.  
##Tech Stack
Flutter
Visual Studio Code
Dart
Google Cloud
Golang
PostgresQL
Rest Api’s
Android Studio
## Accessibility
Accessibility considerations are important for any product. In our application, we ensure all text is WCAG AA Accessible in color.

## Product Branding
### Color Scheme

Since a user opens our app intending to reduce worrying thoughts, our color scheme must be simultaneously inviting and soothing. We accomplish the first aspect by having friendly and warm accent colors like orange and yellow. The light blue is connotated with trust and reliability, traits we want the user to feel when using our app. The green accent color is associated with health and growth which relates to our app’s features.

A soothing and “easy-on-the-eyes” effect is created by using a softened dark neutral as the background color. Additionally, our app uses a dark mode style design intended to be unalarming for users.

### Logo Design

For the logo, we wanted to emphasize the principle of personal growth while incorporating our product’s name. The symbol of a “check” mark and an “up” arrow were used as the base of the logo. The shapes are rounded to give a softer image to the overall brand. The icon is colored to vaguely represent the look of a tree, a symbol representing the concept of growth.

### What's Next?
There were plenty of features the developers and user research participants wanted to incorporate into our product. If we had more time, here’s how we would improve Check-Up.

### Check-In Limit
This feature would allow a user to set a numerical limit to how many times they can check certain listings on the app. For example, they are only allowed to check if the car door is locked 5 times. Adding this limit motivates a user to exercise self-control over compulsive checking, further promoting healthy relief for intrusive thoughts.
### Metrics Report
This feature would show the user how many times they checked the app and certain tasks. This could be a simple count or graph for different tasks. There could also be a compliment report where the app congratulates the user on a decrease in checking. Displaying these metrics would motivate a user to practice healthy avoidance of checking compulsions.
### Intuitive Color Coding
This feature would change the colors of the tasks if they were completed. Then the user would know at a glance if their task was completed.
### Google Home/Amazon Alexa Integration
With this feature, Check-Up could be synced with a smart home device for more ease with checking. As an example, the user could ask Alexa if they already locked their car.
### Password Authentication System
For extra account security, a password authentication feature is good to have.
### Light Mode
This feature is solely for user visual preference. Users could toggle between light and dark mode.
### Home Screen Banner Notifications
This feature would allow a user to use Check-Up without having to go through the extra steps to open the app.
## Challenges  

### New to Hackathon

TAMUhack 2022 was the first hackathon that 75% of our members had ever participated in. The process involved learning about how to manage time strategically and what to prioritize. When we realized that we would not have time to implement all the features we wanted the app to have, going through our list of features and deciding what was critical for the competition vs. which tasks would be stretch goals was a challenge.

### Learning Tech Stack

Several members of our team were not familiar with Flutter and Dart, the tech stack we chose for this project. During the first few hours of the hackathon, our team did not make much progress because we had to learn the basics of app development in Flutter.

During the middle phase of development, one of our team members tackled Google Cloud Platform with little to no prior experience. Due to the team’s unfamiliarity with Google Cloud Platform, several hours of time were wasted trying to resolve issues that weren’t there or not noticing problems with configurations that needed to be addressed.

### Asynchronous Programming, Concurrency, and Race Conditions

The app we developed requires the ability to read/write to/from the device’s memory and the Google Cloud Platform. Since external reading and writing involves blocking system calls, the majority of our application had to be run through asynchronous programming. Many hours were spent researching and debugging asynchronous programming, concurrency alternatives, and race conditions.

## Accomplishments
### Creating a Product as a Team

All of our team members have been friends since middle school We got to spend the weekend reuniting with each other and working as a team. More importantly, we were able to come together to create a product we believe will help students like us.

## What We Learned
**Maximilian Deitrick**

With this being my first hackathon and such, this whole experience has been a great opportunity to learn new skills. This project was written in a language that was new to me and now, nearing the end of the 24 hours, I can confidently say I want to do this again next year. During this project, I worked alongside Ryan, as he taught me the ins-and-outs of the language. I ran into roadblocks fairly often, but I worked through it with. And with his help, and a lot of documentation, I persevered. Specifically, I got to understand how to implement the camera on your phone into an app and store the file to later be played back to the user. While this is just a small part of what there is to learn, it has paved the way for me to learn more about this topic in future hackathons to come.

**Kunal Gupta**

This hackathon was an amazing opportunity to put my software skills to the test in a time-constrained, competitive environment. I felt much more motivated to learn and dedicate extended periods of time to developing because I felt passionate and confident about our product, enjoyed the opportunity to work with close friends, and had my eyes on the amazing prizes. I learned a new language and framework, and I set up a Google Cloud Platform project with a Cloud SQL instance and an associated microservice API deployed to the Cloud all from scratch, which I am immensely proud of. I can’t wait to continue using GCP for future projects!

**Brianna Navas**

The first time I attended a hackathon I left early because I was scared to compete. I was always intimidated to attend hackathons because I felt like I couldn’t contribute to the team. When I worked with my friends this year, I learned I can contribute in ways not directly related to programming. I was able to use my passion for UX and marketing in creating complete branding and advertisement for our product. Additionally, I was able to make important front-end design decisions. I’ve used Canva in the past for products but I wanted to experiment with the new video editing feature. This hackathon was a great opportunity to learn how to use the video editing feature.

**Ryan Radloff**  

This is my 10th hackathon, and I had a blast showing three of my long time friends all the joys (and some of the frustrations) of hacking. I spent most of my time this hackathon designing and building out the flutter front end. As I have almost exclusively worked as a backend dev at previous hackathons, there was plenty to learn. One of the biggest challenges I had when designing the frontend was handling a race condition when reading file input asynchronously. Consequently, I learned a ton about how asynchronous functions work in Dart as well as new ways to handle Futures. This also was my first hackathon working with a very UI/UX focused developer. This was a great experience overall as I got helpful feedback to make the app look better and learned plenty of ease of use tips that I can personally apply to my development practices.
