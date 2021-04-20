![](BookThinkers.png?raw=true)
<hr>

# Project Title
BookThinkers Life-Changing Books - Book Lovers Community Application

# Background
## Who is BookThinkers?
BookThinkers is an education-media company that cultivates a large community of book enthusiasts and authors. BookThinkers help authors promote their books by interviewing them on the BookThinkers podcast. BookThinkers helps expose avid-readers to great new books through the BookThinkers Instagram (111,000 followers). You can read more about them [here](https://www.bookthinkers.com/). 

## What Are We Building For Them? (Project Goals)
### Overall (By The End of The Semester)
Deliver an intuitive web-app and native iOS App equipped to serve four core functions for book lovers.
1. Maintain a personal bookshelf. Track the books you've read and enter reviews and notes about key learnings from each book.
2. Socialize with other booklovers. Add friends. Follow book influencers and read their activity.
3. Create a reminder based retention system to periodicially notify you to reread your book notes to assist with long-term retention.
4. Gamify the app with badges.

Implement the necessary functions for administration of the application. 
1. Create an administrative dashboard for the BookThinkers team to view and manage user data and basic analytics.
2. Implement a payment solution to facilitate premium subscriptions to the application.

### Sprint 1 (Build the backend)
1. Model our data and build an interactive database for the web and mobile application.
2. Set up our hosting services.
3. Familiarize ourselves with the tools we will be working with. 
4. Set up views (Web & Mobile) for authentication (sign in with Google or manually create an account via email).

## Why This Project?
The BookThinkers team receives extremely frequent and repetitive inbound requests through their Instagram account asking for the solution we hope to provide. Many users want ideas for how to retain their learnings from the books they read. Many also indicate a desire to connect with other book lovers as they don't have real world friends who share their interest in books. 

Additionally, BookThinkers has conducted a few surveys of their audience and the features described in the goal section were the most commonly requested.


# Our Approach
## Backend
We are implementing the backend with a combination of different services provided by Firebase. This primarily includes their Realtime Database and Hosting solutions. For the books database, we will be using either Amazon's or Google's Book API.

## iOS App
The native iOS App will be built with the Swift programming language. In addition, we will use a few frameworks including Firebase SDK, UIKit, and SwiftUI. For dependency management, we will use Cocoapods.

## Web Application and Company Administrative Dashboard
The website will be built using HTML, CSS, SCSS, Node.js, Angular.js, and Typescript.

# User Experiences
As briefly described in the goals section, this app provides four main benefits to users.

### Improving Learning Outcomes (Goals 1 and 3)
BookThinkers aims to provide an app that allows readers to consolidate their biggest takeaways from the physical, digital and audiobooks that they are reading. For example, a BookThinkers Instagram follower may join the app/website using their gmail account. They may have finished reading _Thinking Fast and Slow by Daniel Kahneman._ This book is incredibly densely packed with powerful ideas. Using our app, the user would log that they read the book, add it to their bookshelf, and leave a review. In addition, they would be prompted to leave notes on what they learned from reading the book. Finally, the user would be asked how often they want to be reminded to revisit those notes. Based on their response, the app will reintroduce notes at specific time intervals to maximize retention using notifications. There will be different “pathways" depending on the frequency that each reader is open to. This spaced repetition technique is used by the world's most effective learners to help facilitate the process of learning.

### Creating A Social Community (Goal 2)
There will be a social activity feed where users can see what their friends (other users of the app) are reading and “book threads” where you can chat with other users about each book. This will be the homescreen for logged in users. The feed will incude updates from BookThinkers team (such as new podcast episodes), and reviews from the users that the current user is following or friends with.

### Gamification (Goal 4)
The users are able to view the badges that they have earned and that are available to earn by completing a series of challenges. Some badges will be earned by socializing (having 10 friends for example), others will be triggered by finishing onboarding steps (logging your first book for example), and completing prescribed reading pathways (reading all the books by a specific author for example). Users will be able to see what badges are available, what it takes to achieve them, and the badges they have earned. 

### Administration Functions
The BookThinkers staff will be able to log into a simple website that shows them analytics and provides control of the database. This can be used for granting users free access to premium memberships, moderation and removing problematic (vulgar for example) content and users, and creating the requirements for book based badges. 

# Team Members
- Preston Evans
- Andrew Jerome
- Elijah Sawyers
- Louis Shulman

# Final Video

<iframe width="560" height="315" src="https://www.youtube.com/embed/hsRvvWkY46A" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
