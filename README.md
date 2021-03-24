# EdifyOnline - Junior Developer Challenge
#### This test will assess your skills with the main technologies used on the EdifyOnline platform. You will be started to be evaluated at the moment that you receive the e-mail with this GitHub repository.
---  

## Problem
You will need to develop a simple application with signup and login features. The application will work based on two models: User and Pet. At the moment that the user is siging up, he should be able to set the fields: name, email, password and ONE pet name. A callback should be triggered to add two more pets, with name that you may choose, after the user is created. When successful login/sign up, the user should be redirected to a page that will list all his pets names. At the listing page, it should have a button that will "alert" a random listed pet name.

Write a rake task which will call a Job (ActiveJob). This job will receive a user_id as param and will update all his pet names to "Sirius".

You don't need to store user session or any kind of auth token. Don't worry about design/styling the application. You should worry about split the page in components that makes sense.
Vue.js don't need to be embbed in the Rails app, you can develop in two separe projects if you want, just make sure to push both projects to the same GitHub repo.

Use GitHub in your development process. You are allowed to use any libraries you want. Try to follow all best practices that you may know. Your logic and code will be reviewed. Less is more!

Even if you was not able to finishing all steps, you can proceed and submit the challenge. You will be evaluated for what you have done.

---
### Models
- User
    - id
    - name
    - email
    - password
    - created_at
    - updated_at

- Pet
    - id
    - name
    - created_at
    - updated_at

### Requirements:
- Rails API
- Vue.js
- PostgreSQL
- Validations
- GitHub

### Not required but good to have:
- Model and Controller tests with RSpec
- DRY/Clean code
- Descritive git commits
- Anything that you think it will improve your challenge (be creative :D)

---
<br></br>
After finish, answer the e-mail with the link to your git repository. Any questions? Feel free to get in touch with me
> mateus@edifyonline.com


_Good luck, have fun!_

<br></br>

*"I think it is possible to ordinary people to choose to be extraordinary" - Elon Musk*
