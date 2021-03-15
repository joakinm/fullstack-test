# Overview
	You have a patch with 14 commits in which you'll findd a responsive chat app, (a module with 2 components and a router with 2 pages) made in Angular framework
	
# Installation steps
	The steps for making this work are:
	- Clone the repository
	- Patch was made for windows, if you have linux, mac or unix, you must edit EOL conversion (with notepad++ go to Edit/EOL conversion and unix for linux or machintosh for mac)
	- Open a terminal and run "git apply chat-test.patch"
	- When you have all done, you'll need to run "npm i" or similar, in order to install all dependencies you need in this folder: /node-modules 
	- Run the proyect with "ng serve"
	- By default, the port is 4200, so go to a navigator and go to http://localhost:4200
	
## Profile page:
	- Have a header with the name of the user in the top
	- Have a rounded profile photo with a status in red to indicate the user is offline, or green if is online, 
	  if youclick the photo, it will redirect you to the chat page
	- Have name, age, country, description and a star, and if it is fullfilled is your favourite user
	- Have a button "add as friend" at the botton, when the user clicks it, changes the button and header background color to yellow.

## Chat page:
	- Still get the previous header,
	- A chat interaction, at this time with a bot, that sends a response everytime you write a message, 
	  It will take 1 second to appear "is writing...", and 3 seconds after the response is shown 
	- If you click the profile photo, it will send you to profile page
	
## Code
	- You will find all code in /src/
	- profile component in /src/app/profile
	- models in /src/app/models
	- Chat component in /src/app/chat
	- Global styles in /src/styles.css
	
# What would I have done differently if I had more time? I would...
	- Make the header in a new component, and reuse it in all the views
	- Make a WYSIWYG toolbar
	- Make an edit and delete message options
	- Make a match page with more users
