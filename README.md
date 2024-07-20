Task Prompt: Social Media Like Notification System

Objective:
Design and implement a feature for a social media platform that sends email notifications to users whenever their posts are liked by other users.

Technologies to Use:

1) Passport.js: Implement authentication for users.
2) Multer: Handle image uploads for user profile pictures and post images.
3) Nodemailer: Send email notifications to users.
4) Mongoose: Define schemas and interact with MongoDB for storing users, posts, and likes.
5) ImageKit (optional): Manage and optimize images.

Task Requirements:

1) User Management:

Implement user registration and authentication using Passport.js
Allow users to log in and maintain sessions.

2) Post and Like Functionality:

Create a MongoDB schema for users, posts, and likes using Mongoose.
Define a schema for posts that includes fields for the post content, image uploads using Multer, user who posted it, and an array of users who liked it.
Implement the ability for users to like/unlike posts.

3) Email Notification System:

Integrate Nodemailer to send emails when a user likes another user's post.
The email should include:
Subject: "[Your Social Media Platform]: Your post was liked!"
Body: "Hello [Username],\n\nYour post on [Social Media Platform] was liked by [Liker's Username]. Check it out!\n\n[Link to the liked post]\n\nBest regards,\nThe [Your Social Media Platform] Team"