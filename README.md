# Angular Interview Questions

The goal here is to provide a complete guideline to get that job in angular


## Table of Contents
* [Start with yourself]()
* [Know the interviewer](#research-the-interviewer)
* [Beginners level: Terminology related questions](#what-category-questions-angular-terminology)
* [Beginners level: Doability related questions](#question-to-verify-you-did-some-work)
* [Beginners level: Understandability related questions](#question-about-understanding)
* [Intermediate level: Terminology related questions]()
* [Intermediate level: Doability related questions]()
* [Intermediate level: Understandability related questions]()
* [Expert level: Terminology related questions]()
* [Expert level: Doability related questions]()
* [Expert level: Understandability related questions]()
* [Beginners level: Understandability related questions]()


## Understand Your Current Level
The most important step to get that job is to understand yourself. your skill. your strength and your weakness as well. If you don't feel confident about any part. Do a favor yourself by googling and spend few minutes to go throw some blog or youtube videos. 

* If you can create a angular app by using angular-cli or any other seed. also understand component, module, pipes, service, etc. you can consider yourself in the beginners level.If you don't have any clue what I am talking about, watch this [video](https://www.youtube.com/watch?v=rOr1r1rSZQ8) and follow steps.
* If you have full functional app that is deployed somewhere or have code in github. you understand detail about routing module breakdown, unit test, styling, build etc., you can consider yourself in intermediate level
* If you master in lazy loading, AOT, you can put yourself in the expert level
* Rest of the people are either angular dumb or angular rockstar. 


## Research Interviewer
Do a favor to yourself. Goggole the interviewer. Look at his/her linkedin provile. Check whether he/she has any youtube video, talk or active blog. and after your research try to put the interviewer in one of the following category
1. Lazy interviewer asks about terminology. Sometimes they google questions and ask you from there. For them see the Termninology related questions
2. Modest and nicer interview wants to check whether you can get the job done. and you know stuff. For this kind of interviewer look at the How category questions
3. Smart interviewer wants to know that you think, you compare and analyze stuff to make consious decisions. For these type of nerdy inteviewer (they would love to prove you wrong. and one important tip: don't try to prove them wrong) you should study why type of questions


Research the team. Search people in the linked in by company name and then look their profile in github. 


## Beginners Level

For the beginners level an interviewer wants to know whehter this interviewee is self learner, trainable. Hence he/she wants to know you are familiar with basic terminology, coded something and understand why you are using some part in a very high level.  


### What Category Questions( Angular Terminology)
1. What are the difference between angularJS (angular 1.0) and angular2?
2. What is a component? why would you use it? 
1. What is the minimum definition of a component?
3. What is a module and what does it contains?
5. What is a service and why will you use it?
5. What is a promise? Explain it in simple words.
7. What are the  life cycle hooks for component and directives?
8. What is pipes?
9. What is a pure pipe?
1. What is dumb component



### How Category (Verifies you developed something)
1. How do components communicate with each other?
1. How do you create two way data binding in Angular?
6. How you build an angular app for production
6. How would you run unit test 
7. How you create custom pipes
8. Which life cycle hook will you use to unsbscribe a promise
1. How can you get current state of a route
2. How will you protect a route for authorized user only
1. How to use http service to load data from serve
1. How are the services injected to your application?



### Why Category (Verifies you Understand)
2. Why would you use angular-cli 
3. What are the difference between a component and a directive
6. Why would you use typescript aka benefits of typescript


Answers link coming soon 


## Intermediate Level

you built angular2 you played with routing, https, different built process, unit test, etc. here are the questions you could expect

In the intermediate level you are very comfortable with angular. Hence there is no what questions. Actually you know all of them by now. Hence there will be only how and why type questions


### What Category Questions
1. What is the difference between RouterModule.forRoot() vs RouterModule.forChild()? Why is it important?
1. What is the difference between an observable and a promise?
1. What are some of the angular apis that are using observables?
1. What is the difference between a module's forRoot() and forChild() methods and why do you need it?
1. What is a structural directive?
1. What pseudo-class selector targets styles in the element that hosts the component?
1. What's the difference between dirty, touched, and pristine on a form element?
1. What is a structural directive?
1. What is an async pipe?
1. What kind of data can be used with async pipe?
1. What is the difference between ngOnInit() and constructor() of a component?
1. When will ngOnInit be called?
1. How would you make use of ngOnInit()?
9. What is authGuard 




### How category questions
1. How do components communicate with each other?
1. How do you create two way data binding in Angular?
1. What is the purpose of NgModule?
1. How do you decide to create a new NgModule?
1. How do you identify a structural directive in html?
1. How would you select a custom component to style it.
1. How would you select all the child components' elements?
1. How would you make use of ngOnInit()?
1. How would you cache an observable data?
1. How will you inject header
1. How would you create a custom pipe?
1. How would you pass data from a parent component to a child component?
1. How would you pass data from a child component to a parent component?
1. How would you cache observable data?
1. How do you mock a service to inject in a unit test?
1. How do you mock a module in a unit test?


### Why category questions
1. Why angular2 uses decorator
1. When will ngOnInit be called?
1. Why do you need type definitions?
1. Which components will be notified when an event is emitted?
1. Why would you create shared module?
1. What would you not put shared module?
1. Why would you export from ngModule?
1. Why is it bad if SharedModule provides a service to a lazy loaded module?
1. What is the difference between an observable and a promise?
1. Can you explain the difference between ActivatedRoute and RouterState?
1. which service will you put in the module and why
1. What is async validation and how is it done?



answers coming soon



## Expert Level

you just built hello world in angular2+ and may be you followed some video or blog and now you are brave enough to tell the interviewer that you know little bit angular2. 

### What Category(just few bonus)
1. what is factory Component
1. What is lazy loading
1. what is AOT
1. What are some of the Angular Style Guide suggestions you follow on your code? Why?
1. what is wildcard state?
1. How do you put animation between two states?
1. How will you do lazy loading in angular application
1. What would be a good use for NgZone service?
1. How would you protect a component being activated through the router?
1. How would you insert an embedded view from a prepared TemplateRef?


### How Category
1. How will you http interceptor
1. How you parallelize multiple observable call
1. how will you put one async call before another

1. What tools would you use to find a performance issue in your code?
1. What are some ways you may improve your website's scrolling performance?
1. Explain the difference between layout, painting and compositing.
1. When does a lazy loaded module is loaded?
1. How do you identify a structural directive in html?
1. How would you create a component to display error messages throughout your application?


### Why Category
1. How would you implement a multiple api calls that needs to happen in order using rxjs?
1. How would you make sure an api call that needs to be called only once but with multiple conditions. Example: if you need to get some data in multiple routes but, once you get it, you can reuse it in the routes that needs it, therefor no need to make another call to your backend apis.
1. If you need to respond to two different Observable/Subject with one callback function, how would you do it?(ex: if you need to change the url through route parameters and with prev/next buttons).



Answers link coming soon 


## Coding Test

1. you just built hello world in angular2+ and may be you followed some video or blog and now you are brave enough to tell the interviewer that you know little bit angular2. 
2. How would you implement a brush behavior using rxjs?
3. How would you implement a color picker with rxjs?


Answers link coming soon 

Few questions are inspired by [Yonet](https://github.com/Yonet/Angular-Interview-Questions)