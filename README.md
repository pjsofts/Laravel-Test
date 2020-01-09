# Create A TODO App
## General Application
The user will use this app to 
1. Add TODO items to a list.
2. Edit and Delete items in the list.


## Backend
In the backend use Laravel.
1. Design the database.
2. Write CRUD APIs for the todo model.
3. Do validation on the incoming queries from the front-end.
4. Add sort by creation date to todo list.
5. Add Search on tickets based on title. If the title contains the query entered the result should return it;
6. **(optional)** If you like, you may add user management and authentication
    - Each user can see the items posted by other users.
    - Each user can only edit/delete items posted by themselves.
7. **(optional)** If you like, you can have a set public/private button
    in front of each todo item, public todo items can also be edited/deleted by other users.
8. **(optional)** Adding a Role-Permission mechanism for users have extra points.
    (e.g. a user may can add and edit it but another user may have all the permissions to delete store ,
    also different roles can be set to users (e.g. admin,regular users))
9. **(optional)** Send an email to user after adding a todo item to inform him that the item has been added.
    (implementing with job or event/listener has extra points)


## Frontend
1. Simply use Blade to render plain HTML forms.
2. **(optional)** If you know any front-end technologies you may use it
 to render a better UI/UX experience.
    - You may use CSS to style the form.
    - Or you may use Bootstrap components.
    - Or you may use JQuery for posting the form, or doing validation on the client.
    - If you know React, Vue or Angular you can use them to create a reactive UI.
 

## Infrastructure
1. Push your code to a github/gitlab repository and share it with us.
1. **(Optional)** If you enjoy doing this, you may publish your web application on 
Heroku container-based cloud Platfrom as a Service (PaaS) free tier and share the link with us. 