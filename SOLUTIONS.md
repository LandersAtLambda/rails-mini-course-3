### Rails MVC

First, start the rails server. Then, make a request to `/tasks/new`, fill out the form and submit it in order to create a new task.

1. What controller and action handles the data from the form submission?

    - `tasks_controller` and `create` handle the form submission

2. What controller and action would be used if you did a `GET` request on the `/users` route?

    - `users_controller` and `index` action

3. Write out the step-by-step process that your rails application will take to render the `tasks/new` route.

    - Request comes in and goes to `routes.rb` --> `tasks_controller` --> `models/task.rb` --> `views/tasks/index.html.erb`

4. What file is responsible for managing the mapping between your application and the `tasks` database table?

    - model file

### Rails RESTful Actions

5.  Explain all 7 of the RESTful actions in Rails

    -   List each action by its name
    -   Explain which HTTP verbs pair with each action
    -   Write a short sentence for each action that summarizes what it does

            - index

                -   GET - Gets all of whatever the controller is managing

            -   show

                -   GET - Shows just one itme of what the controller is managinng

            -   new

                -   GET - Displays the form to create a new item

            -   edit

                -   GET - Displays the form to edit an item

            -   create

                -   POST - Endpoinnt for creating the item in the database

            -   update

                -   PUT/PATCH - Endpoint for updating the item in the database

            -   destroy

                -   DELETE - Update for deleting the item from the database
