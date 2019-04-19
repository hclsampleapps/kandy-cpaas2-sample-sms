# kandy-cpaas2-sample-sms

### SMS app

This app is used to create communication channel between two users via SMS APIs.

 - [Try it now](https://hclsampleapps.github.io/kandy-cpaas2-sample-sms/app/) at playground
 - Get the [source code](https://github.com/hclsampleapps/kandy-cpaas2-sample-sms)

#### User manual 

1. Create an account on **AT&T** portal via [Register now for a free account](https://apimarket.att.com/signup).
2. Open `index.html` in the browser.
3. Enter the *server URL*, for e.g.,
	- For AT&T API Marketplace [apimarket.att.com](https://apimarket.att.com), enter *https://oauth-cpaas.att.com*
4. Choose to get accessToken by *Password Grant* flow or *Client Credentials* flow.
5. For **Password Grant** flow, enter 
	- *clientId* 
	- *emailId* 
	- *password*  
	- *phone number*
6. For **Client Credentials Grant** flow, enter
	- *privateKey*
	- *privateSecret*   
7. Click ***Login***
8. Open two instances of `index.html` in the browser for *user1* and *user2*.
9. Login using two different user's credentials in both the browser windows.
10. After successful login you will get an *accessToken* for user1 and user2, that you can use to send/receive SMS between both the users.
11. Click ***Subscribe*** button in both the browser windows to create the webrtc channel.
12. Enter the user2's *User ID* or *Phone Number* into the user1's browser window ***Create Conversation*** box; e.g.,
	- User ID: *janedoe@somedomain.com ([userId]@[domain])*, or
	- Phone Number: *+12223334444 (+[countryCode][areaCode][subscriberNumber])*
10. Click on ***Create*** button to create the conversation between both the users.
11. Enter the text message into the user1's *Message* box and Click on ***Send*** button.
12. Open the user2's browser window and check the *Message* box, if message received than type a message into the user2's *Message* box and click on ***Send*** button.

##### Notes

 - Existing user can confirm their account via [Log in to AT&T API Marketplace](https://apimarket.att.com/login)
 - You can download *kandy.js* from [Developer documentation - SDKs](https://apimarket.att.com/developer/sdks/javascript)

### Development

To setup the project repository, run these commands

```
git clone https://github.com/hclsampleapps/kandy-cpaas2-sample-sms.git
cd kandy-cpaas2-sample-sms
```

Then, open ```index.html``` in the browser to view the app.

#### Branching strategy

To learn about the branching strategy, contribution & coding conventions followed in the project, please refer [GitFlow based branching strategy for your project repository](https://gist.github.com/ribbon-abku/10d3fc1cff5c35a2df401196678e258a)
