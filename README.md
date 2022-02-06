# HackSC22-GroupHub

Inspiration:- 

Communicating and being able to connect with people is often difficult when you have negative emotions building up inside of you. Many people with anxiety limit their interactions and experience sadness or frustration as a result. Group therapy is an effective mental health treatment that encourages people to communicate with others and explore their emotions, instead of hiding them. This boosts their confidence and helps them cope in social situations better.
From this, we ended up with GroupHub, an online platform to connect people facing similar problems in their lives. It helps one find like-minded people or just a friend to talk to during tough times.   

What it does:- 

GroupHub is a Web Application that allows users to join various kinds of group sessions to talk about their everyday problems. When users first come on the site, they will be given an option to Signup/ Login or directly chat with the chatBot. Users are greeted with a welcome message by the chatBot and asked to enter their name, this will enable them to add their name to the pool of existing users so that next time our chatBot can recognize them. Based on users' responses to chatBot’s questions they are given a link to the page that would have a list of the most appropriate group sessions for the user. From there, they’ll be able to choose and join whichever session they feel like joining. 

How we built it:- 

Wix, the base of the web application, interface design, and flow of the application,
FireBase DB, a cloud-hosted real-time database, to store all of the information about our users and keep track of all their feelings!
Agora,  a Real-Time Engagement Platform to allow embedding group video calls in our web application.  
Dialogflow, a natural language understanding platform to design and integrate a conversational user interface into our web application. 
Kommunicate, for intelligent chat-based support.

Challenges we ran into:- 
  - We were new to Dialogflow, so we had to quickly familiarize ourselves with its working.
  - We were not able to add a URL to Dialogflow chatbot response, as we were using the free version. We had to search for software to provide a wrapper over existing Dialogflow agent. We used Kommunicate for this, it enabled us to add a URL to our chatbot responses. 
  - We wanted to create our own video conferencing web app. This needed us to read up  and experiment with tons of APIs on how to enable video and audio conference features. We finally created a webpage that used Agora API to enable multi-client video conferencing. 
  - We also spent a lot of time deciding what database to integrate with our application. We decided on using Firebase DB but had to spend time reading the documentation as we had never used it before. 

Accomplishments that we're proud of:- 
  - There were many technologies that we were not familiar with like DialogFlow, Agora, Firebase. We also had to brush up on our web technologies skills like HTML, CSS, Javascript. However, we ensured that we spent time learning their concepts and were successfully able to implement and integrate them. 
  - We came up with a project idea that was novel and a quick way for users to find solace among all the uncertainties of the Covid Pandemic. We are proud of the fact that we tried to do our part for public wellness. 

What we learned:-
- The connection between the front and back-end applications
- Implementing APIs, specifically Agora, for group video call 
- How to use real-time databases like Firebase
- Coding in JavaScript, which most of us did not know before
- How to implement and integrate our AI-based agent on Dialogflow with our front-end code and back-end database.

What's next for Group Hub:-

  We hope to add:-
  
    - More features to our DialogFlow chatbot, which recognizes more user attributes to improve customization during the navigation to the most appropriate virtual group session. 
    - Extend our web app into a mobile application with voice input recognition from the user to the chatbot. 
    - Automize the creation of virtual rooms on a need basis whenever a particular user comes up with a new issue. 
    - Use the user's history to create a user character profile. This will help the Ai assistant to make even better decisions while suggesting group sessions. 


