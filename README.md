# kandy-sample-sms

### SMS app

This app is used to create communication channel between two users via SMS APIs.

#### Steps 

1. Create an account on **AT&T** portal via [Register now for a free account](https://apimarket.att.com/signup).
2. After signup get the following 
	- *clientId* 
	- *emailId* 
	- *password*
	- *phone number*
3. If you are an existing user, please [Log in to AT&T API Marketplace](https://apimarket.att.com/login).
4. Download *kandy.js* from [Developer documentation - SDKs](https://apimarket.att.com/developer/sdks/javascript)
5. Open two instances of ```index.html``` in the browser for user1 and user2.
6. Login using two different user's credentials in both the browser windows.
7. After successful login you will get an *accessToken* for user1 and user2, that you can use to send/receive SMS between both the users.
8. Click "Subscribe" button in both the browser windows to create the webrtc channel.
9. Enter the user2's User ID or Phone Number into the user1's browser window "Create Conversation" box; e.g.,
	- User ID: *janedoe@somedomain.com ([userId]@[domain])*, or
	- Phone Number: *+12223334444 (+[countryCode][areaCode][subscriberNumber])*
10. Click on "Create" button to create the conversation between both the users.
11. Enter the text message into the user1's Message box and Click on Send button.
12. open the user2's browser window and check the message box, if message received than type a message into the user2's message box and click on send button.
