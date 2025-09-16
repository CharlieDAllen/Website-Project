[README](../../README.md)

# Purpose
The purpose of this project is to produce a simple, functional, intuitive social media platform that is to the quality of a professional end user product.

# Project Scope:
## Functional Requirements:
### Must Haves:
- Ability to create a user account with a username and password.
- Ability to login and log out of your user account.
- Ability to add and remove friends from a friends list.
- Ability to follow and unfollow users.
- Ability to recieve notifications when others add you as a friend and or follow you.
- Ability to share textual and image (JPEG) based content publicly.
- On the feed the ability recieve content made by other users on the platform.
- The ability to directly message other users textural content.
### Should Haves:
- Custom taloured timeline based on connections.
- Ability to tag content to better configure it for the algorithm.
- User blocking that stops others being able to interact with you.
- Liking and disliking on posts.
- Commenting on posts.
- User search bar
- Content search bar
- Ability to delete own account
- Ability to change account to private (removing all posts publicly)
- Ability to change follow requirements to on-approval.
- Ability to change direct messaging requirements; (any, followers only, friends only)
- Ability to customise user profiles with information about themselves.
- Ability to add profile picture and background images to profiles.

## None - Functional Requirements:
- Usability - the user interface should be intuitive, allowing a new user to understand basic functionality within 5 minutes of use.
- Performance - The website shall load content within 3 seconds on a standard mobile connection and the feed will be optimised such that hours of scrolling on one page does not crash your device.
- Security - All user passwords must be securely hashed and salted. All communication between the front-end and back-end shall be encrypted using SLL / TLS
- Maintainability - The codebase shall be modular and well - documented to allow for each future enhansements.

# Use Cases:
## Account Creation
## Account Login / Log out
## Following and Unfollowing
## Notification System:
1. User is present on the website doing any number of things.
2. The user recieves a notification to alert them something important happened, a friend request, follow, comment, follow request. . . etc.
3. The user clicks on the notification to be taken to the relevant page or the user discards the notification.

## Content Posting:
1. A user wishes to share content publicly.
2. They go to the navigation bar.
3. They go to the make a post web page.
4. They enter the textual and image content they wish to post.
5. They view a previous of their post before it goes live.
6. They confirm and the content goes live.

## Feed:
1. A user enters the website.
2. They wish from the feed.
3. They click on the 'feed' web page on the navigation bar.
4. They scroll through content recommended to them.

## Timeline:
1. A user logs on for the day.
2. A user wishes to view more relevent content from people they potentially know. (connections)
3. They go to their timeline page.
4. They receive content from connections. (friends and people they are following)

## Direct Messaging:
1. User wishes to privately message a user.
2. They go to their profile.
3. They click message.
4. The user sends a communication.
5. A back and fourth conversation (potentially) starts.

## Content Tagging:
1. A user wishes to post public content.
2. The user creates the public post and adds hashtags to encourage the recommendation algorithm to recommend this to specific tags.

## Liking / Disliking a Post:
### Scenario 1:
1. A user is scrolling the feed or timeline.
2. They see content they like / dislike.
3. They leave feedback via a like or dislike.
4. Their recommendations are updated and the post is boosted or surpressed.

### Scenario 2:
1. A user makes a post.
2. Other users give feedback via likes and dislikes.
3. The recommendation algorithm adapts based on this.
4. The user is given feedback based on those mtrics.

## Commenting:
1. A user views a post they wish to interact with.
2. The user clicks the comment button on the post.
3. The user leaves a public comment.

## User Account Searching:
1. A user wishes to find a specific user by username.
2. They go to account searching.
3. They search for the account.
4. Accounts of similar semantics is returned.

## Feed Searching:
1. A user wishes to browse a specifc type of content.
2. They go to the search bar.
3. They search the content they wish to view.
4. Similar content is recommended to them via the feed.

## Account Deletion:
1. A user wishes to delete their account and all accosiated data.
2. They go to account settings.
3. They click delete account.
4. They are prompted to enter their username and password.
5. A window pops up confirming as this cannot be undone.
6. They are required to enter there password again.

## Changing Account to Private:
1. A user wishes to make their content private but not delete their account.
2. They go to their settings.
3. They toggle make account private.
4. They confirm.

## Changing Follow to On-Request:
1. A user wishes to change their follow requirements
2. They go to profile settings.
3. They toggle on-follow request.
4. They save the changes.

## Changing Direct Messaging Requirements:
1. A user wishes to change their direct messaging requirements.
2. They go to profile settings.
3. They toggle direct messaging settings (any, followers only or friends-only)
4. They save the changes.

## Profile Customisation:
### Profile Pictures:
1. The user wishes to add a profile picture to their account.
2. They go to their account settings.
3. They upload their profile picture.
4. They view what it looks like before it goes live.
5. They click confirm or deny and it goes live. (if confirm)

### Background Image:
1. The user wishes to add a background image to their account.
2. They go to their account settings.
3. They upload a new profile background.
4. They view what their profile would look like with the background image.
5. They click confirm or deny and it goes live. (if confirm.)

# Wireframes and UIs
![Desktop Wireframe Pages](./Design_Diagrams/Wireframe_Views/Website_Wireframe_Design_Desktop.pdf)

# References
[Project Charter](../Project_Charter.md)
[Technical Feasability Study](../Technical_Feasibility_Study.md)
[Project Plan](../Project_Plan.md)

#### Contributors
[Charlie Allen](../Contributors/Charlie_Allen.md)