# CIS355_FINAL
Final project for cis355 

Gonna use tailwind css and an external script file

Description:

This application will be a sort of college friend finder, chatting app, etc. College students will use this app and it will help them meet people with familiar interests, same major, same age group, etc. People can make public posts to ask questions or share whats happening. 


Page 1: Login / sign up page: The user can create an account or log in to an already existing account. 

Page 2: Home page, this will be where posts pop up. It will get the users location and show posts in that area. User can sort by newest, top, school. 

Page 3: Create post: A form to write what you want to be posted on to the page, it will be posted according to their location so the people with the same area see it.

Page 4: Shows one post with all of its replies. This is where a user will add a reply and/or vote on the post.

Page 5: User profile: Shows the users own posts, replies, etc. they can delete or edit their posts from here. 

External API: I plan on using OpenStreetMap Nominatim API. It will give us the users coordinates which is sent to Nominatim to return a readable location. 

Database:
Users: userID, username, password, school.
Posts: postId, userID, postText, area, latitude, longitude, dateCreated.
Replies: replyID, postID, userID, replyText, dateCreated
Votes: voteID, userID, postID, voteValue(upvote or downvote, +1 or -1)
-------------------------------------------------------------------------------------------------------------------------------------------------------

11/23/26 2:17pm:

I added to the signup page (which will continue to just be a vague look at the home page but not as in depth)
I added some comments so you will know which id's will link to what features but i think the only one i did so far is the X button on the signup page
i already created the const for that and added the event listener to add hidden to the popup, check script.js
I also linked the browse groups button to the second html file called home.html

next thing im going to do (later) is find a database to use, not sure how to do that but ill learn how to set one up. google says to use MySQL. I will set that up and connect it soon.
