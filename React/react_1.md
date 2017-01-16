This is the description of tasks that are used in our mentoring process. We wanted to create an opportunity for you to show us your skills and work style, but also to polish your knowledge and familiarity of tools and technology - both of HTML markup with CSS stylesheets, and Javascript frameworks.

The project consists of progressive phases, where each task explore more skills and adds more complexity. Whenever you stuck or encounter problems - don't be shy, talk to us, show what's wrong and we will try to help you.

Beside fulfilling project tasks you can also present your abilities in terms of:
•	HTML templating languages (HAML, Slim, etc)
•	styling frameworks (Compass, Bourbon, etc)
•	other tools you use and want to show us

For this purpose, the resulting source code should be available for us to review (not only compiled code, but all sources too).

Same goes for JS framework - we use for our projects Angular (and we suggest it for you too), but if you want to use another one - no problem! You're fed up with all the JS frameworks? Seeing another Model-View-SmartThingy makes you want to run away crying loud and because of that you prefer Vanilla JS solutions? Show us how you roll! 

Please explain every choice you make on the way and place all arguments for the way of development you prefer. Even if your development approach is vastly different that our own, your accomplishment still can be valuable to us and use of different tools or technology won't disqualify you. Just provide us with your context, so the more we know, the better results from review.

Whenever task description or provided pictures does not provide enough information about any aspect of implementation, we dare you to spot it, describe and make a decision on your own (with additional reasoning for chosen approach). If you don't feel competent enough, you can always ask us about details.

Provided views pictures: https://dl.dropboxusercontent.com/u/80779637/Mahisoft/Mentoring/React_1.zip

Font used in design is Rotice, but you're free to use any similar replacement.

Task 0: Set ambient

Set a dev ambient for a Javascript Backend and Frontend development. Install and run a helloworld with:
Backend: 
•	Node.js
•	Npm
•	N (version manager)
Frontend:
•	Sass
•	Foundation (optional)**
•	React
•	Redux/Flux
Others:
•	Github
•	Docker/Vagrant

** = If you want to support your work with Foundation (containing ready to use components and styles), you're allowed to. If you want to write everything on your own - please do! In both cases additional reasoning explaining your choice is greatly appreciated (if you make a decision upon not valid reasons you will loose this points)

Task 1: Implement views

Your first task is to implements 3 base views of this project: list of questions (all_questions_base.png), single question view (single_question_base.png) and user profile (profile_base.png). Bottom line is just static view, with HTML markup and CSS stylesheets, however you can connect them with links for easy switching from view to view.

Task 2: Make them responsive

User profile and single questions view have additional versions for tablet and mobile. For all questions view use additional material which pictures way the single story box is changing with responsiveness. How should other interface elements act for different viewports? Came up with your own solution for this part.

Task 3: Connect modal to users

As you noticed so far, user profile is displayed as modal. Write necessary logic for displaying user profile modal while visiting both question views and show this modal whenever user avatar or name is clicked.

Task 4: Use templates

If so far you've coded all the content for questions, comments and profile data within HTML now is time to leverage that to templates. Make the data reside in dedicated data structures and collections. Every place that can potentially hold varying content should use templates and fill it with data from collections. If you feel competent enough try mocking API requests but all the data still can be fixed (no backend is needed for this project, but if you know how to talk to JSON API, here is your chance to show how it's done from browser side).

Task 5: Add pagination and sorting

All questions view has interface dedicated for sorting questions - use it and implement sorting items displayed here. At the bottom of list is 'load more questions' command. Add functionality which shows additional number of questions within this view when clicked (all the data can be fixed even if it means repeating items).

Task 6: Add search

All questions view has search form. Use it for implementing simple search system and let it show only items related to provided query (when search is run with empty query just show all the items, like by default visit to this view).

Task 7: Implement voting

Single question view contains comments and answers with voting component. Implement voting component, so viewer can rate entries as helpful or not.

Task 8: Add routing

If so far views were connected just by standard hyperlinks, now it's time to go SPA way - combine all views in single app and make them switch without reloading browser.

Good luck!
