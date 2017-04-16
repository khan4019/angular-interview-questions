# Angular Interview Questions

The goal here is to provide a complete guideline to get that job in angular. This repo is in baby stage. So feel free to slap with pull requests.


## Table of Contents
* [Understand Your Current Level](#understand-your-current-level)
* [Know the Interviewer](#know-the-interviewer)
* [Beginners Level](#beginners-level)
    * [Familiarity to Basic Terminology Questions](#familiarity-to-basic-terminology)
    * [Ability to Build Simple App Questions](#ability-to-build-simple-app-questions)
    * [Understanding Basic Concepts Questions](#understanding-basic-concepts-questions)
* [Intermediate Level](#intermediate-level)
    * [Essential Terminology Questions](#essential-terminology-questions)
    * [Comfortability to Build Medium Size App Questions](#comfortability-to-build-medium-size-app-questions)
    * [Core Concepts Understandability Questions](#core-concepts-understandability-questions)
* [Expert Level](#expert-level)
    * [Performance and Edge Case Related Terminology](#performance-and-edge-case-related-terminology)
    * [Master a Large App Related Questions](#master-a-large-app-related-questions)
    * [Rockstar and Fighter for angular Questions](#rockstar-and-fighter-for-angular-questions)
* [Coding Test: Coming soon](#coding-test)
* Understanding Side things Related Questions (will born soon)
    * testing
    * build and deploy
    * es6
    * rxjs
    * typescript
    * zonejs    
    * material2
    * localization/ translation
* Tools expertise related Questions (keep your pant tights for this)
    * angular-cli
    * build tools


## Understand Your Current Level
The most important step to understand yourself. If needed improve your skill, strength and confidence. If you don't feel confident about anything, do a favor tjo yourself by googling and spend few minutes to read some blog or youtube videos. And then check which level you are in terms of your angular skills.

* If you can create a angular app by using angular-cli or any other seed. Also understand component, module, pipes, service, etc. you can consider yourself in the beginners level. If you don't have any clue what I am talking about, watch this [video](https://www.youtube.com/watch?v=rOr1r1rSZQ8) and become beginners level.
* If you have full functional app that is deployed somewhere and/or published code in github and you understand detail about routing module breakdown, unit test, architecture, etc., you can consider yourself in intermediate level angular developer.
* If you master in lazy loading, AOT, custom directive, deployment configuration, etc. you can put yourself in the expert level.
* Rest of the people are either angular blind or angular rock star. 


## Know the Interviewer
Do a favor to yourself. Google the interviewer. Look at his/her Linkedin profile. Check his/her youtube videos, old blog that wasn't developed in years and github profile. After your research try to put the interviewer in one of the following categories.
1. Lazy interviewer asks about terminology. Sometimes they google questions and ask you from there. They mostly ask termninology related questions. Mostly old managers ask these type of questions.
2. Modest and nicer interview wants to check whether you can get the job done. and you know stuff. For this kind of interviewer look at the How category questions
3. Smart interviewer (the guy who is a senior developer for a long time and has updated blogs and videos) wants to know that you think, you compare and analyze stuff to make consious decisions. For these type of nerdy interviewer (they would love to prove you wrong. and one important tip: don't try to prove them wrong) you should study why type of questions


Research team  member as well. Search people in the linked in by the company name and then look their profile in github. 


## Beginners Level

For the beginners level an interviewer wants to know whether this interviewee is a self learner, trainable. Hence he/she might asks question about basic terminology, your ability to build some simple app and high level understanding.  


### Familiarity to Basic Terminology
1. What are the difference between angularJS (angular 1.0) and angular2?
2. What is a component? why would you use it? 
3. What is the minimum definition of a component?
4. What is a module and what does it contains?
5. What is a service and why will you use it?
6. What is a promise? Explain it in simple words.
7. What are the  life cycle hooks for component and directives?
8. What is pipes?
9. What is a service and why would you use it?
10. What is a dumb component? and what are the benefits of dumb component?



### Ability to Build Simple App Questions
1. How do components communicate with each other?
2. How would you use http to load data from server? 
3. How do you create route in angular app?
4. How can you get current state of a route?
5. How do you create two way data binding in Angular?
6. How to load external module in angular app?
7. How you build an angular app for production?
8. Which life cycle hook will you use to unsbscribe a promise?
9. How are the services injected to your application?
10. How would you create route parameter and access it from a component?



### Understanding Basic Concepts Questions
1. Why would you use angular over some other framework like react?
2. What is the difference between an observable and a promise?
3. Tell me the difference between a component and a directive?
4. Why would you use typescript aka benefits of typescript?
5. Why different life cycle hooks is needed for a component/directive?
6. Why angular uses rxjs?
7. What is the purpose of using zone js?
8. What is the difference between ngOnInit() and constructor() of a component?
9. When will ngOnInit be called? How would you make use of ngOnInit()?





[Answers link coming soon ]


## Intermediate Level

In the intermediate level, you built medium size angular app and you played with routing, https, different built process, unit test, etc. here are the questions you could expect



### Essential Terminology Questions
1. How will you protect a route for authorized user only?
2. What is a custom pipe and how will you use it?
3. What is a structural directive?
4. What is the difference between RouterModule.forRoot() vs RouterModule.forChild()? Why is it important?
5. What is the difference between a module's forRoot() and forChild() methods and why do you need it?
6. What's the difference between dirty, touched, and pristine on a form element?
7. What is an async pipe? What kind of data can be used with async pipe?
8. What is injectable? Give me some example.
9. What is a pure pipe?
10. How will you create two way data binding in Angular?



### Comfortability to Build Medium Size App Questions
1. How do components communicate with each other?
2. How do you decide to create a new NgModule?
3. How will you inject custom header in your http call?
4. How do you identify a structural directive in html?
5. How would you select a custom component to style it?
6. How would you select all the child components' elements?
7. How would you cache an observable data?
8. How would you cache observable data?
9. How do you mock a service to inject in a unit test?
10. How would you run unit test? 



### Core Concepts Understandability Questions
1. Tell me about feature module and shared module?
2. What would you not put shared module?
3. Why angular uses decorator?
4. What is async validation and how is it done?
5. Why do you need type definitions?
6. Which components will be notified when an event is emitted?
7. Why would you export from ngModule?
8. Why is it bad if SharedModule provides a service to a lazy loaded module?
9. Can you explain the difference between ActivatedRoute and RouterState?
10. Which service will you put in the module and why?



[Answers link coming soon]



## Expert Level

You are a rockstar in angular. you can teach other. you can lead a team for angular project. you should know the answer to the following questions.

### Performance and Edge case Related Terminology
1. What is factory Component?
2. What is lazy loading and why will you use it?
3. What is Ahead of time (AOT) compilation and why will you use it?
4. What are some of the Angular Style Guide suggestions you follow on your code? Why?
5. What is wildcard state?
6. How do you put animation between two states?
7. What would be a good use for NgZone service?
8. How would you protect a component being activated through the router?
9. How would you insert an embedded view from a prepared TemplateRef?
10. What is attribute directive and why will you use it?

### Master a Large App Related Questions
1. How will you intercept http to inject header to each http call?
2. How would you create a component to display error messages throughout your application?
3. How you parallelize multiple observable call?
4. How will you put one async call before another?
5. How can you use web worker in angular app?
6. What tools would you use to find a performance issue in your code?
7. What are some ways you may improve your website's scrolling performance?
8. Explain the difference between layout, painting and compositing.
9. How can you cancel a router navigation?
10. How would you animate routing?


### Rockstar and Fighter for Angular Questions
1. When does a lazy loaded module is loaded?
2. Why angular uses url segment?
3. How will you make angular app secure?
4. how will you localize numbers currencies and dates?
5. What is the best way to use translation in you app?
6. How will you setup different environment build differently for you app?
7. How will you use scss or css preprocessing with your application?
8. How will you optimize image/svg in your angular app?
9. How would you make sure an api call that needs to be called only once but with multiple conditions. Example: if you need to get some data in multiple routes but, once you get it, you can reuse it in the routes that needs it, therefor no need to make another call to your backend apis.
10. If you need to respond to two different Observable/Subject with one callback function, how would you do it?(ex: if you need to change the url through route parameters and with prev/next buttons).




[Answers link coming soon]

## Coding Test
This part coming soon
2. How would you implement a brush behavior using rxjs?
3. How would you implement a color picker with rxjs?


Answers link coming soon 

Few questions are inspired by [Yonet](https://github.com/Yonet/Angular-Interview-Questions)