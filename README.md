# Introduction
Congrats in passing the first round of interview! 
Kindly find the project assignment. 
You have 8 hours to complete your assignment. 
Do remember to consistently push your progress so that we are able to track! 

# Getting Started
You will need to use the **following technologies** for the project: 
- nodeJS for backend 
- mongoDB for database 
- NextJS for frontend
- agora.io for video recording and capturing. Please visit https://www.agora.io/en/developer-resources/ for more information.

# Project Details <br />
We are automating the interview process by allowing candidates to submit their video interviews online! 

**For the user flow:** <br />
1. When the candidate goes into the page, they see a registration form for them to input important details 
2. After the candidate signs up, they are directed to a page to take the video interview test
3. The video interview uses the agora.io API to record and capture and store the video. 
4. The video interview question will be shown, and the user will be able to record the video, and confirm the video they want to submit. 
5. Please note that the maximum length of the recorded video should be 1 minute. 

**FOR BACKEND** <br />
Create the backend service using nodeJS and mongoDB.<br />
You will need the following models: 
1. Candidate (talent that takes the test)
2. Video Interview
3. Video Interview Questions
4. Maximum video length for the candidate to answer questions (you can hardcode it to be 1 minute)
Feel free to add other models that you think you may require. 

**FOR FRONTEND**<br />
The front-end does not need to be fancy. 
Please use NextJS template for the frontend. 

**METRICS**<br />
You will be assessed based on:
- clean code
- good design of databases etc. 
- error handling 
- threading safety
- coding best practices / design patterns

**BONUS - STRETCH PROJECT**<br />
Create a form that after submitting with the relevant interview details (interview questions, max video length) generates a unique URL that allows companies to share the link to candidates. 
