# Omnichannel Room Opener - Rocket.Chat

### **BE CAREFUL, use responsibly to not overload your server with too many rooms.**

This Python script can open at least 5k rooms with visitor information from the public API https://randomuser.me/.

*Change the **url_rc**, **department** and **count** variables at **main** file.*

Keep at least one livechat agent online.

External libraries: requests.

API Documentation: 

- Random User: https://randomuser.me/documentation
- Rocket.Chat Room: https://developer.rocket.chat/reference/api/rest-api/endpoints/omnichannel/livechat-endpoints/livechat-room/livechat-room-info 
- Rocket.Chat Visitor: https://developer.rocket.chat/reference/api/rest-api/endpoints/omnichannel/livechat-endpoints/visitor/register-a-new-livechat-visitor
PS: If you have a department, this info must go at Rocket.Chat Visitor.
