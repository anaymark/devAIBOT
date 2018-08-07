## The Why?

### Today messaging apps have become the fastest growing and most used apps as measured by time spent on mobile apps by users. 

![]( ./public/assets/Mobile_App_Usage_Growth.png?raw=true "Mobile App Growth")

### People love to chat, and social interaction is the hands down best medium to reach the largest amount of people. 

### Come Facebook Messenger, it is a platform that is now reaching true gloabal reach(number 1 platform in USA and top 3 in most countries).

![]( ./public/assets/Mobile_App_Usage_By_Country.png?raw=true "Mobile App Usage, Country")

### Messaging apps have also surpased social networks in monthly active users and are presenting exponential growth!

![]( ./public/assets/Mobile_App_Usage_Monthly.png?raw=true "Mobile App Usage, Monthly")

![]( ./public/assets/Mobile_App_Usage_Growth_WhatsApp.png?raw=true "Mobile App Growth")

### Not only does Facebook have reach, but it now shown that daily time spent in messaging and social apps has been growing at an extremely rapid pace YOY: close to 70%!

![]( ./public/assets/Mobile_App_Time_Spent.png?raw=true "Mobile App Growth")

### All these growth factors presents a huge opportunity in all realms of Business and customer engagement/interaction. 

### We live in an age where everything is expected to occur very fast and always straight to the point. Business responce time is one of the most essential parts of finding and engaging new customers, building a customer base, and keeping loyal customers happy. 

![]( ./public/assets/Mobile_App_Business_Response_Time.png?raw=true "Mobile App Growth")


### *This is where chatbots become one of the most useful untilities of this decade* for businesses of all scale. Most people have used chatbots in one way or another, and some may not have even known it. There is a wide range of chatbots being deployed for customer support among other customer facing automation. 

![]( ./public/assets/Mobile_App_Business_ChatBots.png?raw=true "Mobile App Growth")

### We live in the age of instant gratification, where communication favors speed and conciseness. However, the single greatest advantage of chatbots over anything that has come before, is the fact that people still value human communication, or what is percieved to be human communication. Chatbots will usher in a new era of evolution for what is percieved as human communication and create a completely new medium for not only business/customer engagement, but human interaction will also come to be blended with AI interaction in an almost indistinguishable difference between the two. 
### Communication preferences are shifting from Phone and Email to messaging applications. This shift has begun to usher in the era of the chatbots, an era that will experience unprecedented growth when combined with virtual reality possibilities. 

![]( ./public/assets/Mobile_App_Communication_Preference_vsEmail.png?raw=true "Mobile App Growth")

![]( ./public/assets/Mobile_App_Communication_Preference_vsPhoneCall.png?raw=true "Mobile App Growth")

### The why is an endless list. I am not becoming interested in the what and how. However, the why always drives the vision and direction. 

## The what?

### Currently I am new in this realm and interested in learning everything I possibly can in NLP, Deep Learning, and modern conception of AI.

### For beggining my journey I have decied to create a Facebook Messenger bot that will teach others how to create bots for free, and have the reach of a global platform. Education is being revolutionized with the reach of current interaction mediums. I am currently embarking on a project that will hopefully evolve over time to deliver a virtual classroom that will teach others how to create their own virtualbots and spread the interest in Artificial Intelligence for the betterment of humanity.

# Here's a small introduction and demo of where I am starting and what I am doing: 

[![](https://img.youtube.com/vi/4ae6hBVdPgg/0.jpg)](https://www.youtube.com/watch?v=4ae6hBVdPgg)


## The How 

## Steps to deploy your own Bot so it will run through the codebase and not directly from Facebook Messenger to DialogFlow are listed below. This is useful for creating advanced features, creating a database, access 3rd party API's, etc. This is what will make your bot useful and create unlimited possibilities. Node.js is the platfrom of choice for now along with Heroku for deployment. 

### You will need familiarity with the following technologies:

* Node.js
* Express.js
* Heroku/Heroku cli
* Git/GitHub
* DialogFlow formerly API.ai
* API access/consumption
* bash/terminal/cli
* Facebook Developer-Messenger
* Database of choice has not been determined yet but most likely MongoDB or PostgreSQL(pick any backend you would like, FireBase could be good for something like this)
* At some point you will also need hosting for files that you want your bot to serve. There are many options for how to serve these files and what to use, I will cover these at a later date. 

1. Fork or clone this repository. This code will be the skeletal barebone for creating a FaceBook messenger chatbot. 

2. Look through the app.js file and make sure to read through all of the codebase for basic understanding. 

3. Create or sign-in to a Facebook Developer Account, create a new Facebook App with the desired name for your bot, and create a new or use an existing Facebook Page where you will deploy your bot. 

4. Create or sign-in to DialogFlow and create a new Agent for your bot. 

5. You will need the following enviromental variables:
    FB_PAGE_TOKEN: Accessible in the Facebook App
    //page subscription verify token
    FB_VERIFY_TOKEN: token you create, make a complex string
    API_AI_CLIENT_ACCESS_TOKEN: Found in Agent Settings
    FB_APP_SECRET: Accessible through Developer Dashboard
    SERVER_URL: Your heroku server you deploy the code to

5. Create a heroku app, either through the heroku cli or on the heroku website.

6. Add the heroku remote to your forked or cloned repo. 

7. Push the code to your new app.

8. Set the enviromental variables above to your new heroku app.

9. Integrate to facebook messenger through DialogFlow integrate tab. 

10. Subscribe to events using the webhook callback that is your new DOMAIN from your heroku app and webhook as such: <DOMAIN EXAMPLE>/webhook/  

11. Subscribe to basic events such as messages and message_callbacks. Add any others you want. 

12. Subscribe the new Facebook page you created to events through messenger dev dasboard.

13. Enter the page access token and verify tokens to the DialogFlow bot integration and start your app!

14. If you followed everything, you should now have your bot say hello when you go to your facebook page->view as visitor->send message.

15. Get creative through building cool bots!

16. I will be creating tutorials and more on using DialogFlow. I have basic intents and contexts introduced in the videos here: 

[![](https://img.youtube.com/vi/qC0D1Px-go4/0.jpg)](https://www.youtube.com/watch?v=qC0D1Px-go4)

[![](https://img.youtube.com/vi/V-_qe-5Ndjo/0.jpg)](https://www.youtube.com/watch?v=V-_qe-5Ndjo)

### This is the beginning of a virtual educator bot that I am trying to build and help people learn cool things! 

## The possibilities for messaging bots and virtual reality are endless. Let's explore these possibilities together. I am always open to collaboration and can be reached through github or through [Sashas Club](https://www.sashasclub.com/contact/)

Resources: 

* [DialogFlow](https://dialogflow.com/docs/getting-started)
* [Facebook Developer](https://developers.facebook.com)
* [Facebook Messenger for Developers](https://developers.facebook.com/docs/messenger-platform/)
* [Heroku Get Started with Node.js](https://devcenter.heroku.com/articles/getting-started-with-nodejs)
* [Learn basic CMD](https://www.codecademy.com/courses/learn-the-command-line/lessons/navigation/exercises/your-first-command)





