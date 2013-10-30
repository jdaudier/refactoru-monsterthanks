# Monster Thanks

### Description:
Monster Thanks is an interactive thank you card that enables _real-time_ collaboration among multiple participants.

![Monster Thanks](https://dl.dropboxusercontent.com/u/125982/monster-thanks-screenshot.png)
### Steps:
1. Start a card
2. Share the link with all your friends
3. Choose your background
4. Choose a monster and drag it to the card
5. Add a message bubble next to your monster
6. Other recipients of the link can come and add their own monster
7. Save the card when everyone is done with it
8. Send the link to the recipient (card is locked)

### Client-Side
* Handlebars
* Stylus

### Server-Side
* Node
* Express
* Jade
* MongoDB
* Mongoose

### Client-Server Communication
* Web sockets (Sockets.io)
* AJAX (?)

### Bonus (if I have time)
* Ability to change out the font style for "A monster thanks from all of us" header message
* Copy link feature (like GitHub)
* Send email with link to other participants
* Send email with link to recipient
* User can come back and edit the text or change monster

### Questions:
1. How do I load the monster (along with the position and message bubble) that someone else has created before me?
2. Is it hard to make it real-time where I can see when someone else is adding stuff (like Google docs)?
3. How do I auto save?
4. How do I lock the card?
5. How do I create message bubbles using CSS-transformations?
6. I can't figure out how to resize a SVG (together with dragging).
7. I can't figure out how to drag an item outside of its parent div (to the right side of the page)