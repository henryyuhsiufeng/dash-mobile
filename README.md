# dash-mobile
This is the mobile application of my personal project called Dash. 

- The goals is to allow users to join chatrooms via mobile device. The user's desired chatroom id is unique and can only be accessed if the user already knows the id before hand. When a user leaves a chatroom, all the messages are deleted. This creates an interesting mode of communication that enables new opportunities and solutions.

- Possible usages:  
    - ice breakers for small organizations or clubs
    - Communicating with clients without exchanging social media or other sensitive contact information
    - Finding new friends / networking by posting chatroom id's publically

Tech Stack: React Native, socket.io, javascript<br>
UI/UX: Material Design (Still experimenting)

#### Todo:
- Join Page
- Chatroom 


#### Bugs/Fixes
- Find native equivalent to web event.target
    - FIX: Switch to onPress, text => {setMessage(text)}
- For react native buttons. use onPress
- Certain fonts are specific to os of device
- Styling issues
    - realize that styles affect components that have been added

#### Learning Sources
- https://davidwalsh.name/websocket
    - Good read on socket.io and websockets 