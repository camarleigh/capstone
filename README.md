# capstone
Capstone project for ADA

at least two high level ideas for your capstone. For each idea:
show up with a problem statement -- a sentence or two describing problem
people can't do x
i need something in my life that will x
do some market research
is this already out there?
is there open source library that will get you part way?
user persona
what are the characteristics of a user of your project?
who would benefit from or find your project useful?
It'd be great if these ideas were 180 degrees apart, but they don't have to be.
Having more than two is a good idea too.
These ideas are to get you started on Monday morning. Your final capstone project does not have to be directly in response to these ideas.



 Before building your applications, you will need to create a product plan:

 - identify your target audience and their unmet needs.
 - write a project specification to explain how you will meet those needs, including the features to implement.
 - create an incremental delivery plan.
## Delivery
The Capstone Project consists of the following components:
- Completed application, live on the web
- The source code of your project on Github, with:
 - Clear documentation on how to setup/install your project
 - Any third-party dependencies or configuration required
 - A link to your Trello board
 - A link to your Product Plan
- Product Plan: problem statement, user persona(s), market research
- Project presentation, a demo of the application and product plan
## Product Plan Components: Due October 9th.
1. __Problem Statement__: A clear, concise statement describing the problem your project will solve.
1. __Market Research__: Outline the key insights from your research, incuding:
 - your application’s competition - what alternatives are already out there (competing apps and/or non-app solutions)
 - research from users on why these alternatives do not effectively address the problem.
 - differentiation: what makes your idea/product different
1. __User Personas__: A summary of your main target user group(s). What are their key characteristics? How do those characteristics factor into project/app/idea?
## Application: Due October 30th.
The capstone is an individual project, but I encourage you to work together to solve specific problems. You will need to meet all of the goals and guidelines listed below, including at least two ​_advanced features_​ and at least two ​_integrations_​ from (or similar to) the lists below.
### Goals & Guidelines
- Use your product plan to lead the functionality development of their application
- Create and maintain a [Trello board](https://trello.com/) to document progress on your project.
- Host the application using a VPS such as Amazon EC2
- Configure DNS with custom domain
- Create a stylized, responsive design for all devices (phone, tablet, display)
- At least 10 items of seed data for each concept/model
- Use background jobs for any long running tasks (email, image processing, 3rd party data manipulation)
- Use caching for slow or bulky database interactions
- Use performance analytics to assess and optimize site performance (average server response time < 300ms)
- Practice TDD to lead the development process
- Integrate email (At least user signup)
- Expectations for code quality:
   - 90% or greater test coverage (models and controllers)
   - Javascript tests (client and server side) w/ Mocha
   - B- or greater score on Code Climate
   - No security issues (Brakeman)
### Integration Choices
- Choose at least two complex integrations, examples:
 - Background/Async Jobs (sending emails, confirming registrations)
 - NoSql (MongoDB)
 - Content Delivery Network (CDN)
 - Payment Processing (Stripe)
 - Front-end Framework (Ember, Angular, Backbone, etc.)
 - Third-party OAuth (logging in w/ Twitter, Github, etc.)
### Advanced Feature Choices
- Choose at least two advanced features, examples:
 - Secure Socket Layer (SSL)
 - Content Management System (CMS)
 - Internationalization (i18n)
 - Live Events (notifications, live updates, think back to Philip's AWS presentation)
 - Service Oriented Architecture (SOA)
 - S3 storage/delivery
 - Secure Public API (documented)
__Instructors will verify that your choices for integrations and advanced features are appropriate__















Heels, Flats, Sneakers

Not in love with this as a DNS,  could be unintentionally sexist. I need a name that conveys flattest, fastest, hardest.  Will keep thinking about it. 

Problem Statement

Seattle is hilly. Disturbingly hilly for some individuals. While I initially wanted to create this application for myself, I am now aware of other groups for whom it may prove useful.

My idea is a walking map that details not just the fastest walking route, but also the most intense walking route and most importantly, the walking route with the flattest possible elevation, in theory, the easiest route.   

Initially a concern for my feet and heeled shoes, I’ve come to realise this application could be of great help to the medical community as well.  For those beginning or returning to workouts, strenuous climbs are usually advised to be avoided.  This application would be of great use for someone who is starting a workout routine. 

Market Research 

The Competition - 

There are lots of options available to those looking for directions to walk from point A to point B.   And even a few that offer elevation details, but I have not found one that factors that information into the routes it chooses; it’s more like extraneous information.  

Google Maps -  I haven’t completed investigation but I’m pretty sure Google strives to return the fastest algorithm. i.e., this is the fastest distance between point A to point B.  research into the documentation leads me to believe I want to use the Google Maps Javascript API. 

Walkscore -  a copyrighted enterprise I’m not interested in using walkscore any longer. They have pruposely obscured how they’re coming to their elevation information and as this would be a publicly held appilcation, I’m not interested in paying them to use their api either. 

Seattle.gov -  I’m not sure what source seattle.gov is using to create its maps.  My attempts to dissect it have been in vain. It still remains the easiest interface to tell if a street has a steep slope, but not the best as all streets above a certain grade are marked with red. 

Open Street Maps - I find this interface slightly disorienting. I am still exploring it as it seems to be the one most closely linked to NASA’s information.

NASA -   NASA may be  like striking gold for this project, but it may also be bad as I may have hit the motherload instead of a manageable vein.  I haven’t yet figured out how to read all of NASA’s info 
