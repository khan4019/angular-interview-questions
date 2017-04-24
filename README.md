# Angular Interview Questions

A complete guideline to prepare for angular interviews. Also, you can use these questions to verify your expertise in angular. 



## Table of Contents
* [Assess Your Skill Level](#assess-your-skill-level)
* [Know the Interviewer](#know-the-interviewer)
* [Novice Level Questions](#novice-level)
    * [Familiarity to Basic Terminology](#familiarity-to-basic-terminology)
    * [Ability to Build Simple App](#ability-to-build-simple-app-questions)
    * [Understanding Basic Concepts](#understanding-basic-concepts-questions)
* [Intermediate Level Questions](#intermediate-level)
    * [Essential Terminology](#essential-terminology-questions)
    * [Comfortability to Build Medium Size App](#comfortability-to-build-medium-size-app-questions)
    * [Core Concepts Understandability](#core-concepts-understandability-questions)
* [Expert Level Questions](#expert-level)
    * [Performance and Edge Case Related Terminology](#performance-and-edge-case-related-terminology)
    * [Master a Large App](#master-a-large-app)
    * [Rock star and Fighter for angular](#rockstar-and-fighter-for-angular-questions)
* [Coding Test Question](#coding-test)
    * [Fetch Data and Display User Profile](#fetch-data-and-display-user-profile)
    * [Persistent Todo List](#persistent-todo-list)
    * [Student Registration System](#student-registration-system)
* [Side Things Related Questions](#side-things-related-questions)
    * [rxjs](#rxjs)
    * [TypeScript](#typescript)
    * [angular-cli](#angular-cli)
    * [others](#others)
* [Note from God](#note-from-god)



## Assess Your Skill Level
The most important step is knowing how you compare to other job seekers. Pinpoint areas where you are weaker, and spend the time necessary to make improvements. Google is your friend.

* **Novice** - You can create an Angular app using angular-cli or other popular project seeds, you have a basic understanding of components, modules, pipes, services, etc. If you don't have a clue what I am talking about, watch this [video](https://www.youtube.com/watch?v=rOr1r1rSZQ8) and get up to speed.
* **Intermediate** - You have a fully functional app that is deployed somewhere and/or published code in github, and you are comfortable with routing, authorization, feature modules, architecture, style guide, etc.
* **Expert** - You have mastered lazy loading, AOT, custom directives, deployment configuration, extending core features, etc.
* **Everyone Else** - You are either angular blind or an angular rock star. 


## Know the Interviewer
Do yourself a favor—Google the interviewer. Look at his/her Linkedin profile. Check his/her youtube videos, crappy old blog that hasn't been updated in years, and github profile. After your research, try to put the interviewer in one of the following categories:
1. Lazy interviewers wil ask about terminology. Sometimes they just Google and ask questions from there. If your interviewer is older and out of touch with the current development landscape, there is a greater chance that he/she will ask questions related to terminology.
2. More modest and nicer interviewers will be interested in what you know and whether you can get the job done. For this kind of interviewer look at the How category questions (I'm unsure what you are trying to say here)
3. Experienced interviewers (those who have been senior developers for a long time and have recently updated blogs and videos) want to know that you can think critically, and he will be interested in your process for decision making. These interviewers love to prove you wrong. One important tip: don't try to prove them wrong.

Researching relevant team members on LinkedIn and github can be useful as well.

## Novice Level

At this level an interviewer wants to know whether the interviewee is a coachable self-learner. Hence, he/she might ask questions about basic terminology, your ability to build a simple app, and your comprehension of basic concepts.  


### Familiarity of Basic Terminology
1. What are the differences between AngularJS (angular 1.x) and Angular (Angular 2.x and beyond)?
2. What is a component? Why would you use it? 
3. What is the minimum definition of a component?
4. What is a module, and what does it contain?
5. What is a service, and when will you use it?
6. What is a promise? Explain it laymen's terms.
7. What are the lifecycle hooks for components and directives?
8. What are pipes? Give me an example.
9. What are the differences between reactive forms and template driven forms?
10. What is a dumb, or presentation, component? What are the benefits of using dumb components?



### Ability to Build Simple App
1. How do components communicate with each other?
2. How would you use http to load data from server? 
3. How do you create routes?
4. How can you get the current state of a route?
5. How do you create two-way data binding?
6. How do you load external modules?
7. How would you display form validation errors?
8. Which lifecycle hook would you use to unsubscribe an observable?
9. How are services injected to your application?
10. How would you create route parameters and access them from a component?



### Basic Concepts
1. Why would you use Angular instead of another framework, e.g., React?
2. What is the difference between an observable and a promise?
3. What is the difference between a component and a directive?
4. Why would you use typescript aka benefits of typescript?
5. Why different life cycle hooks are needed for a component/directive?
6. Why does angular use rxjs?
7. What is the purpose of using zone.js?
8. What is the difference between ngOnInit() and the constructor() of a component?
9. When will ngOnInit() be called? How would you make use of ngOnInit()?
10. What are the benefits of using formBuilder?




[Answers link coming soon ]


## Intermediate Level

To be in the intermediate level, you have to build at least one medium sized angular app. You have to have familiarity with routing, https, different built process, unit test, etc. here are the questions you could expect.



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
10. How will you create two-way data binding in Angular?



### Comfortability to Build Medium Size App Questions
1. How do components communicate with each other?
2. How do you decide to create a new NgModule?
3. How will you inject custom header in your http call?
4. How do you identify a structural directive in html?
5. How would you select a custom component to style it?
6. How would you select all the child components' elements?
7. How would you cache an observable data?
8. How would you save data from a form control?
9. How Event Emitters works in Angular?
10. How do you mock a service to inject in a unit test?



### Core Concepts Understandability Questions
1. Tell me about feature module and shared module?
2. What would you not put in a shared module?
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

You are a Rockstar in angular. You can teach other. You can lead a team of angular developers.

### Performance and Edge case Related Terminology
1. What is a factory Component?
2. What is lazy loading and why will you use it?
3. What is Ahead of time (AOT) compilation and why will you use it?
4. What are some of the Angular Style Guide suggestions you follow on your code? Why?
5. What is wildcard state?
6. How do you put animation between two states?
7. What would be a good use for NgZone service?
8. How would you protect a component being activated through the router?
9. How would you insert an embedded view from a prepared TemplateRef?
10. What is attribute directive and why will you use it?

### Master a Large App
1. How will you intercept http to inject header to each http call?
2. How would you create a component to display error messages throughout your application?
3. How will you parallelize multiple observable call?
4. How will you put one async call before another?
5. How can you use web worker in angular app?
6. What tools would you use to find a performance issue in your code?
7. What are some ways you may improve your website's scrolling performance?
8. Explain the difference between layout, painting and compositing.
9. How can you cancel a router navigation?
10. How would you animate routing?
11. How would you cancel a promise on which you are waiting?


### Rockstar and Fighter for Angular Questions
1. When does a lazy loaded module is loaded?
2. Why angular uses url segment?
3. How will you make angular app secure?
4. How will you localize numbers currencies and dates?
5. What is the best way to use translation in your app?
6. How will you setup different environment build differently for your app?
7. How will you use scss or css preprocessing with your application?
8. How will you optimize image/svg in your angular app?
9. How would you make sure an api call that needs to be called only once but with multiple conditions? Example: if you need to get some data in multiple routes but, once you get it, you can reuse it in the routes that needs it, therefor no need to make another call to your backend apis.
10. If you need to respond to two different Observable/Subject with one callback function, how would you do it? (ex: if you need to change the url through route parameters and with prev/next buttons).




[Answers link coming soon]

## Coding Test
Sometimes interviewer gives real coding test. Most of us suck on those and feel ashamed of ourselves and then continue to work in the current job. I don't want you to saty in that miserable job. Hence, take the following coding challenges and master them. 

### Fetch Data and Display User Profile

This test has three level
1. Level 1: I am giving you an api https://api.github.com/search/users?q=eric This api takes a query parameter name "q" and passes query string to server. Server returns bunch of users. Now I want you to create a input text box and button so that you can type anything on the text box and hit on the button to retrieve data from the given api. Upon retrieval display total_count and first 10 users in the search result. Detail instruction about this test is available [here](https://github.com/khan4019/github-profile-search)
2. Level 2: Convert each user profile as a router link so that upon clicking on each user profile you will navigate to a route that has "login" property in the route. Pass user.login as route parameter. Create a separate component where you will read the route parameter and then fetch data for that user  by using this api https://api.github.com/users/eric . Please Notice that last part of this api is the user.login (the route parameter that you have passed). Finally display user image and few other information in the component
3. Level 3: use any charting framework that you can find and then create a simple bar chart to display number of followers of first 10 users


This coding test will judge your ability to use services, component, routing, data visualization, external module, observables, etc.

[Sample code link coming soon] 

### Persistent Todo List
This test has three levels
1. Level 1:  Implement a simple todo list where you can add items, mark as done
2. Level 2: Now create few categories of todo list and make it persistence in the browser
3. Level 3: Now use firebase (serverless database) to make todo list persistence across multiple devices

This coding test will judge whether you can pass data and events between components. Also, whether you are leveraging directives and understand difference between component and directives.


[Sample code link coming soon]

### Student Registration System
This test has three levels
1. Level-1: Design a system where students can login to register different courses 
2. Level-2: Add a feature so that faculties on each course can view how many students registered on the courses
3. Level-3: (I need a shower. will add text here after I clean up myself) 

This coding test will judge your understanding of architecture for a large application. Your ability to think and implement module, lazy loading, asset management etc.

[Sample code link coming soon]

## Side Things Related Questions

### rxjs
3. Why unsubscribing is important?
1. What is the difference between map and flatmap?
2. Whare are the different ways you can create an Observable?
4. What is forkJoin, zip, share?
5. Difference between hot and cold observables.

### TypeScript
1. How would you debug a typescript file?
2. How do you implement interface in typescript?
3. How would you call base class constructor from child class in typescript?
4. What is typescript language service?
5. How to declare a custom type?
6. what are some disadvantages of typescirpt? answers [here](https://www.codeproject.com/Articles/1071285/Latest-TypeScript-Interview-Questions-for-Beginner) 

### angular-cli
1. Why would you use angular cli?
2. How would you run unit test? 
3. How do you create application to use scss?
4. How to inject base href?
5. How would you extract webpack config from angular cli project?


### Others
1. What is the use of codelyzer?
2. Will you use Angular Material2?
4. How would you set different config in different deployment server?
5. What do you know about ES6?
6. What is ngUpgrage? Do you know how you can run angularJS and angular side by side?

[Answers link coming soon]


## Note from God
On a press release, God expressed HIS apologies to send the author of this repo to a non-English speaking country and creating weekends. 




## Contributors
* [That JS Dude](https://github.com/khan4019)
* [Jesse M. Holmes](https://github.com/wolfhoundjesse)
* And you?
___________


Few questions are inspired by [Yonet](https://github.com/Yonet/Angular-Interview-Questions), [codeProject](https://www.codeproject.com/Articles/1169073/Angular-Interview-Questions)