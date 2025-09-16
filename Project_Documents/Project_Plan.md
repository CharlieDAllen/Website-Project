[README](../README.md)

# Project Plan:
## Project Overview and Objectives:
### Project Goal:
The primary goal of this project is to make a working, professional grade, robust social media platform. It will be simple but the point is to have a website which does its job well and has no major bugs, it should be usable and understandable along with working on all reasonable devices (phone, tablet, pc, laptop but not a samsung smart fridge for example as thats too niche). This will act primary as a portpholio piece.

The secondary goal is to gain experience in building a project start to finish and gaining the skills and experience of doing so along the way.
### Target Audience:
 What Value Does This Product Provide?:
- Streightforward enviroment to share content: allows users to easily share content peer to peer or with the world.
- Fostering discovery of diverse content: allows users to view content made by people they know and random people based on their likes and wants.
- Facilitating a network: allows users to build up there own network and / or facilitate communication with said network.####
- Peer to peer communication: users can communicate with each other.
#### What Type Of Person Would Use This Product?:
The target audience of any broad social media platform is extremely broad, but in this case 13+ users who wish to:
- Share content with the world to see.
- Communicate peer to peer over the internet with friends and strangers.
- Pass the time by scrolling through posts.
#### User Personas:
Given the scope of this project I do not have time to conduct research so i'm going to make up user personas based on what I believe the types of users which use my platform will be.

##### Person 1: The Content Creator
Alex, 19, University Student

Wants to build an audience for their art/photography
Posts regularly to showcase work and get feedback
Values easy content uploading and discovery features
Uses platform 2-3 hours daily, mostly creating and responding to comments
Frustrated by platforms with poor image quality or limited reach
##### Person 2: The Social Connector
Maya, 24, Marketing Professional

Uses social media to stay connected with friends from different life phases
Primarily consumes content rather than creating it
Values timeline/feed organization and messaging features
Checks platform multiple times daily for quick updates
Wants to discover mutual connections and maintain existing relationships

##### Person 3: The Casual Browser
Sam, 16, High School Student

Uses social media for entertainment during downtime
Scrolls through feeds to pass time between classes/activities
Engages through likes/comments but posts infrequently
Switches between multiple platforms throughout the day
Drawn to platforms with engaging algorithms and diverse content

##### Person 4: The Private User
Jordan, 28, Healthcare Worker

Cautious about online privacy and data sharing
Wants to connect with close friends/family without public exposure
Uses mainly private messaging and friend-only content sharing
Values robust privacy controls and blocking features
Prefers smaller, more intimate social circles online

##### Person 5: The Community Builder
Riley, 22, Recent Graduate

Uses social media to find people with shared interests/hobbies
Actively searches for and follows accounts in their niche areas
Engages heavily through comments and direct messages
Wants to build meaningful connections beyond surface-level interaction
Values search functionality and content tagging systems

### Success Matrices:
Success will be measured by a set of features which are robust and complete vs many features, I will also get friends I know in to review and test my product as users.
# Methodology: Agile Waterfall Hybrid Approach:
## Methodology:
For the MVP I will use the waterfall model, building up the MVP in a structured, planned way with clear milestones and goals.

After the MVP is complete, tested and launched I will work on the high priority features, some are dependent on others but I hope to add 'updates' based on the feature launches, this will still be largely structured but its more about getting a feature / set of features tested and functional rather than shipping a whole second version with 10 more features.
# Feature Breakdown & Prioritization
This MVP is the absolute minimum to be considered a social media platform, high priority features are features that without technically qualifies as a social media platform but will feel like its missing something, like friends example; you don't need friends lists to be a social media platform, but it certainly won't feel complete. Low priority features are 'nice to haves'

## Minimum Viable Product:
#### User Profiles:
Users should be able to create accounts with a username, password, log in, log out, and this is where there content and data is stored.
#### Content Posting:
Users should be able to make public content involving text and images (videos and GIFs are not in the MVP scope). Images must be JPEGs for compression purposes.
#### Feed:
A user should have a feed of posts shown to them (for an MVP, randomness is sufficient)
#### Direct Messaging:
Users should be able to interact with one another through direct messaging, direct messaging will only use text (fine for an MVP as it does its job).
#### Following / Friending:
For a quality social media platform a follow feature (to indicate interest in the profile) and friending (to make connections) is a cornerstone. It allows users to more easily keep in contact and view content from similar users.
## High Priority:
### Upgraded Features:
#### User Profile Upgrade:
Users should be able to customise there profile with a description about them, a profile picture and a background image.
#### Content Posting Upgrade:
Content should be able to be shared using text and images should be able to be shared with more file formats. Users should be able to upload content with PNG, JPEG which is then internally converted and compressed into a JPEG. (Videos and GIFs to implement are very complex so lower priority given time constraints)
#### Feed:
A users feed should be recommended to them based on a basic algorithm based on their interests and what they previously enjoyed. Enjoyment will be measured using 'likes' and 'dislikes'.
#### Direct Messaging:
Users should be able to upload and send images in direct messages like with content sharing.
### New Features:
#### User Timeline:
A timeline should show the public content of friends and people they are following, as to keep up with their connections.
#### Content Tagging:
Users should be able to set tags for there content so the algorithm is given pointers on how to recommend it.
#### User Blocking:
You should be able block and unblock users, meaning they cannot message you or view your content. And the person blocking doesn't view them.
#### Liking, Disliking:
Users should be able to like and dislike content based on their preferences.
#### Commenting:
Users should be able to make text comments on posts. For complexity right now it will be simple singular commenting without tree structures or post reply referencing.
#### Search Functionality:
##### User Searching:
Users should be able to search for users based on username (returning based on similiarity so you don't have the headache of putting an exact username in and not being able to find them)
##### Content Searching:
Users should be able to search for content on their feed, it should return content as normal like the feed usually does but with the algorithm returning content in line with the search.
#### Notifications:
Users should get notifications based on friend requests and DMs (notifications are on platform)
#### Basic Privacy Controls:
Users should be able to have the option to:
- Delete there account.
- Change their account to private (removes all posts publicly).
- Change follow to requiring request.
- Change direct messaging requirements (any, followers only, friends only).
# Technical Considerations:
## Authentication and Security:
DJango has many built in security features, Authentication, CSRF tokens, login cookies and Encryption will be handled by django and assumed it is secure.

Direct messages will not be encrypted as this adds lots of complexity that goes beyond the scope of this project.
## Data Validation:
To make a robust website, I will ensure where possible, everything has validation, error catching and fallbacks.
## Content Moderation:
In a true launch, you would have such tools, but it goes beyond the projects scope.
## File Storage:
In a true developer enviroment postgreSQL likely has its own storage server/s, but in this case it will all be hosted on one machine.
## Scalability Concerns:
True scalability goes beyond the scope of this project but the use of PostgreSQL and DJango supports scalability.
# Milestones:
For the MVP they will be concrete milestones, but beyond to the 'high priority' features they will be a cycle but not as structured.
## Project Kick-Off:
## Project Design:
- Software Design Specification
- Design Documents
## MVP Front and Backend:
Code the front and backend, testing and debugging
- Create the MVP of the front end (parallel to backend)
- Create the MVP features backend (parallel to frontend)
- Create and debug the database (needed for backend)
## Integration and Debugging :
- Integrate the front and backend with a web-server, test and debug.
## Iterative Improvement:
- Improve the project based on the 'high priority' list. This is more about different version vs a big set of milestones.
#### Contributors
[Charlie Allen](./Contributors/Charlie_Allen.md)