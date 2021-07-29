# Django-ChitChat
An asynchronous chatting platform
This is a chat platform made entirely using Django framework, channels and python. 
<br>
The asynchronous feature of chat is implemented in this project. The usual wsgi hosting won't work in this case.<br>
The focus is on asgi. 
<br>
We can make chat rooms just using a url parameter and share to add other users in the same room. The chats are never stored and started new when refreshed.<br>
Every user is an unknown user, no login or signup is required.
<br>
