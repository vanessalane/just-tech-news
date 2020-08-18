# Just Tech News

An app that uses Node and Express to emulate the backend of Hacker News.

deployed api: https://glacial-retreat-13736.herokuapp.com/api/

## Models
* Comment
* Post
* User
* Vote

## Comment Routes
* GET `/comments/`: all comments
* DELETE `/comments/:id`: delete comment by id

## Post Routes
* GET `/posts/`: all posts
* GET `/posts/:id`: get post by ID
* POST `/posts/`: add a post. Body should include `title`, `post_url`, and `user_id`
* PUT `/posts/upvote`: upvote a post. Body should include `post_id`, and `user_id`
* PUT `/posts/:id`: update a post's title. Body should include `title`
* DELETE `/posts/:id`: delete a post by ID
* GET `/posts/`: all posts

## User Routes
* GET `/users/`: get all users
* GET `/users/:id`: get user by id
* POST `/users/`: add a user. Body should include `username`, `email`, and `password` (password is hashed with bcrypt)
* POST `/users/login`: validate login credentials. Body should include `email` and `password`
* PUT `/users/:id`: update a user. Body should include any user info you want to update
* DELETE `/posts/:id`: delete a post by ID



