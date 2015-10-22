ProductPlan.md


 - identify your target audience and their unmet needs.
 - write a project specification to explain how you will meet those needs, including the features to implement.
 - create an incremental delivery plan.
 ## Product Plan Components: Due October 9th.


1. __Problem Statement__: A clear, concise statement describing the problem your project will solve.

 

Seattle is hilly. Disturbingly hilly for some individuals.
There are no walking map interfaces that display routes with notification of extreme elevation changes. 


Introducing Heels, Flats, Sneakers

The application will return three routes from entering two points:
  a Heels Route: one with little to no elevation change.
  a Flats Route: the most time-efficient route
  a Sneakers Route: of the three, the one with the most elevation changes in it. 

(Not in love with this as a DNS,  could be unintentionally sexist. I need a name that conveys flattest, fastest, hardest.  Will keep thinking about it.)



2. __Market Research__: Outline the key insights from your research, incuding:
 - your application’s competition - what alternatives are already out there (competing apps and/or non-app solutions)
 - research from users on why these alternatives do not effectively address the problem.
 - differentiation: what makes your idea/product different


There are lots of options available to those looking for directions to walk from point A to point B.   And even a few that offer elevation details, but I have not found one that factors that information into the routes it chooses; it’s more like extraneous information.  

Google Maps -  I haven’t completed investigation but I’m pretty sure Google strives to return the fastest algorithm. i.e., this is the fastest distance between point A to point B.  research into the documentation leads me to believe I want to use the Google Maps Javascript API. 

Walkscore -  a copyrighted enterprise I’m not interested in using walkscore any longer. They have pruposely obscured how they’re coming to their elevation information and as this would be a publicly held appilcation, I’m not interested in paying them to use their api either. 

Seattle.gov -  I’m not sure what source seattle.gov is using to create its maps.  My attempts to dissect it have been in vain. It still remains the easiest interface to tell if a street has a steep slope, but not the best as all streets above a certain grade are marked with red. 

Open Street Maps - I find this interface slightly disorienting. I am still exploring it as it seems to be the one most closely linked to NASA’s information.

NASA -   NASA may be  like striking gold for this project, but it may also be bad as I may have hit the motherload instead of a manageable vein.  I haven’t yet figured out how to read all of NASA’s info.



3. __User Personas__: A summary of your main target user group(s). What are their key characteristics? How do those characteristics factor into project/app/idea?



While I initially wanted to create this application for myself, I am now aware of other groups for whom it may prove useful.

My idea is a walking map that details not just the fastest walking route, but also the most intense walking route and most importantly, the walking route with the flattest possible elevation, in theory, the easiest route.   

Initially a concern for my feet and heeled shoes, I’ve come to realise this application could be of great help to the medical community as well.  For those beginning or returning to workouts, strenuous climbs are usually advised to be avoided.  This application would be of great use for someone who is starting a workout routine. 
 






