## Introduction
Now that you have built 5 portfolio projects, it's time to go back and take them to the next level, as well as familiarize yourself with some of the projects you might not have worked with in a while. You should know the ins and outs of the projects you are using to represent your abilities. You can’t always prepare for the specific questions you’ll get on an interview, but being comfortable showcasing what you’ve already worked on is a big plus. 


Some of the positive feedback we’ve received from employers that have hired Flatiron graduates includes the fact that students are starting out with an understanding of both Ruby and JavaScript. Many concepts are transferrable from one language to another - showing that you know two languages is a good indication that you can adapt what you know to a third language. Knowing both Ruby and JavaScript can also open up more employment opportunities, so it is important to showcase what you know.

## Refactor
Now that you're a React expert, it's a good idea to go back to your projects that use React to refactor and clean up your code. You may want to also add a Rails backend where appropriate. That way you can be sure your portfolio contains multiple projects that are a good indicator of what you can do. You want all the projects in your portfolio to be shining examples of your programming skills!

Refactoring your React code will not only help you review what you’ve learned, but allows you to show that you are thoughtful about structure and readability. One specific challenge for React: components. Components are flexible enough that we could theoretically build our whole app in a single one. It is also possible to go to the opposite extreme and have tons of small components. Refactoring provides an opportunity to find a happy medium: configuring components so they follow logical and readable design patterns. The [official React documentation](link here) provides a guide on thinking in React that might help in identifying what to refactor in your project. 

For Rails, definitely review your MVC structure when refactoring. Students often load a lot of code into their controllers. However, the controller is really just meant to be an interface between your models and views. It should just be handling the ‘business logic’ of your app - based on the request, a controller will get data from a model and use it to render a view. If there is data-related logic present, it should probably be in a model.

Keep the following questions in mind while refactoring:

* Is the code DRY? Is there any redundant content that could be reduced or abstracted? As you're building an app, it is sometimes easier to duplicate code in multiple components than to reorganize the hierarchy of components. Take some time to clean up any repetitive patterns in your code. You might discover a better, more understandable structure for your components that reduces the need for extra code.
* Can you spot any unnecessary or overly complicated code? Along similar lines, the component structure can sometimes lead to convoluted code as we try to get features to work. Occasionally, we try things until something sticks. Sometimes, the moment a piece of code works, we move on to the next task without reconsidering what we’ve written. Now is the time to look back and find examples of this in your project.
* Are there new approaches to achieving what your project does? Programming is constantly evolving. Updating an existing project is a great way to keep learning about new features by trying to implement them in place of existing code.
	• Remember that refactoring shouldn’t change functionality.



## Finish and Add Features
Your project may meet all the requirements that were laid out at the time and be slightly past the MVP stage. However, this does not mean it is fully developed.

Think about what features you can add to bring it to the next level.

You should have communication between your backend and frontend for CRUD functionality in all of your projects. If you already have some basic communication, what else can be added? Are there any backend calls you weren’t able to implement? If you were not able to implement user authentication, try implementing it now.
Are there any external APIs that could be used to boost your project’s functionality?


## For your CSS:

Establish a consistent theme across your app. CSS is often the last thing students work on during their projects, but it can also make your app more visually appealing. Non-technical visitors to the site may not grasp how complicated the code behind it is, but they can definitely recognize if it is well-designed.
Make your app responsive: learn how to use [media queries](link here) to design your project so that it looks good regardless of whichever device it is being viewed on.


## Make Your App Accessible
Another vital addition you should consider for your React project is accessibility. The internet is an essential resource for millions of people, but many websites lack accessibility options, making them difficult or impossible to use for many people.

For more information on web accessibility and why it is important, check out the [World Wide Web Consortium’s Introduction to Web Accessibility](link here). For specific ideas on how you can make your project more accessible, read through the checklist to help guide you.



## Turn Your App into a Progressive Web App
Progressive Web Apps follow specific standards for making a web app function in a similar way to applications built natively on a particular operating system. Among other things, this includes building an application that is functional even if a user is offline or on a poor internet connection.

If you used Create React App to start your project, some PWA functionality is already provided and ready to implement. To learn more about how to convert your app into a Progressive Web App, check out [this guide](link here).

Google also provides a tool that can help you implement your PWA called [Lighthouse](link here). Lighthouse audits your project for performance and accessibility.

## Deploy Your Project
If you haven’t deployed your React project, make sure to do so! As your final project, it is expected to be the most developed project you completed during the software engineering course. Deploying allows you to show off what you’ve built.

We recommend deploying your frontend to GitHub Pages, but you are free to choose what you think is best. Check out [this tutorial](link here) for how to do it. Alternatively, [Firebase](link here) provides free hosting and command-line tools that also work well for this purpose.

For the Rails backend, as with all Rails apps, we recommend [Heroku](link here). Heroku has a free hosting tier that many students have utilized over the years. They also provide a detailed tutorial on how to get your Rails app deployed.

Recommended: Once you’ve deployed your project, make sure to do some quality assurance testing:

* Test every route on your backend. Make sure your frontend and backend are communicating properly.
* Click every link. Make sure there are no bad links on your frontend.
* Navigate around your app in different ways. If a visitor does something slightly unexpected, can your app handle it?
* Open your app using a variety of devices and browsers.
* Share the app with some friends and ask them to play around with it. You might know how things are supposed to work, but giving your app to someone else can identify unexpected user behaviors. Better your friends find bugs than a potential employer!0

Deploying your app is a big plus for building your online presence, but deploying a broken app can be worse than not deploying anything!

[Heroku Deploy](link here?)

## Add a ReadMe
 A strong README is the face of your project. It’s also a valuable opportunity to show your documentation skills and demo what it might be like to work with you on a real project. Most candidates do something basic here, and this is an important opportunity to stand out from the sea of other candidates. Your README should gives interviewers - including non-technical recruiters - a deeper insight into how you approach problems and the technologies you used. 
READMEs should include  wireframes, graphs, gifs, videos, or screenshots showing project design and/or functionality.
Show you can code: make sure you have a link to a live site or if your application is not yet live or is buggy, make a video demo showcasing what your project does. (See the next section for more on recording a video demo.) If you wrote a blog post about your project, link it here.
Check out [this guide](link here) to writing a kick-ass README 


Extra tip: While you can’t embed a YouTube link (i.e. a project demo video) to a README in GitHub, you can include a thumbnail using the code at the very bottom of this article CODE NOT PROVIDED. Adding a YouTube thumbnail isn’t required, but looks snappy. 



## Record a Demo Video
When your project is fully functioning and looking great, record a demonstration of how your app works. Recording a demo allows you to showcase features you’re particularly proud of. It also means you can provide context to your application that may not be apparent from just looking at the app itself.

A demo recording should go through the essential parts of your application. One bonus that comes from doing this: during interviews, you will often need to talk about your projects. If you have a project listed on your resume, assume that you may need to explain what the project is, as well as the challenges you faced during development. A demonstration video will force you to practice this pitch so you’ll be more comfortable when you have to do it live.

A demo recording also acts as an excellent way to introduce yourself. You can use it to show off a bit of your personality. It also shows your ability to communicate complex topics - a critical skill on all tech related teams.



## Conclusion
There are many directions you can go in when upgrading your projects. Having a few well-polished projects is a great capstone proving what you’ve achieved while learning to code. Any time you invest in improving your projects will be beneficial to your job search.
