## Last Week's Accomplishments

> Almost done with the Typescript PR. I went through and finally added all my comments and suggested code changes. I think there is one more issue that needs to be fixed and then I can approve it. I also started on working on a function that will be called onclick. I think I just have to modify the drawRoutes() function and pass in the route that was clicked and then only draw that route that was passed in.

## This Week's Plan

> Going to continue working on the method to display only one route when a button is clicked. I also have to remember that if a button is clicked again, then I need to draw the route again.
> Another idea I have for making this work is maybe adding a boolean in the route object that will just change whenever the button is clicked. I'm not sure if this is doable though, so I will first play with my initial plan.
> Note for myself: look at frontend.js line 241 and modify draw routes to only draw one route instead


## Anything Blocking?

> I think the big PR is going to cause many changes for frontend changes, which is why I'm going pretty slowly with the toggle routes feature. I'm trying to avoid merge conflicts. I'm also concenred that the toggle switch may be getting overridden by the admin controls. If an admin selects routes to be shown, I have to be able to reverse those selections dependig on the route selected by the user.
