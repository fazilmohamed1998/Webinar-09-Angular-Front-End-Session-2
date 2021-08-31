# Webinar-09-Angular-Front-End-Session-2

Scenario 1: Using a sperate router module - Import the RouterModule in app-routing module (app-routing module is already created) and use it in the app module.

 

Scenario 2: Fix the broken delete functionality - If you have noticed our delete functionality is broken after we implemented the http service

   Hint - you may remove the @Output decorator that we used to pass the data to the parent component and try to remove the blog object directly from our service variable.

 

Scenario 3: Fix the bug in view blog component - If you try to reload the view-blog page, you lose the data, this occurs after the implementation of http service since you are not invoking the http method from view-blog component. You need to fix this

                  Hint - you may get rid of the current Blog variable and try implement a getter method instead. Also you might need to use the elvis operator available in JavaScript to stop breaking your template until the data is received.

 

Scenario 4: Edit functionality for a blog - As we have a component to view a single blog post, you need to implement a functionality to edit an existing blog post.

                Hint - you may add an edit button on top of a blog post and redirect to create-blog component and implement the edit functionality using the same form.
