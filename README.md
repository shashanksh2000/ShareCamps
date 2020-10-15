# ShareCamps

> A Node.js web application project that allows user to share their campgrounds and comment on them as a review.

## Live Demo

To see the app in action, go to [https://sharecamps.herokuapp.com/](https://sharecamps.herokuapp.com/)

## Features

* Authentication:
  
  * User login with username and password

* Authorization:

  * One cannot manage posts and view user profile without being authenticated

  * One cannot edit or delete posts and comments created by other users

* Manage campground posts with basic functionalities:

  * Create, edit and delete posts and comments

  * Upload campground photos

* Flash messages responding to users' interaction with the app

* Responsive web design

### Install dependencies

```sh
npm install
```

## Built with

### Front-end

* [ejs](http://ejs.co/)
* [Bootstrap](https://getbootstrap.com/docs/3.3/)

### Back-end

* [express](https://expressjs.com/)
* [mongoDB](https://www.mongodb.com/)
* [mongoose](http://mongoosejs.com/)
* [passport](http://www.passportjs.org/)
* [passport-local](https://github.com/jaredhanson/passport-local#passport-local)
* [express-session](https://github.com/expressjs/session#express-session)
* [method-override](https://github.com/expressjs/method-override#method-override)
* [connect-flash](https://github.com/jaredhanson/connect-flash#connect-flash)

### Platforms

* [Heroku](https://www.heroku.com/)
* [Mlab](https://mlab.com/)
