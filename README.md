# Just Tech News

## Description
A Node app that replicates Hacker News functionality.

deployed app: https://glacial-retreat-13736.herokuapp.com/
deployed api: https://glacial-retreat-13736.herokuapp.com/api

## Endpoints
**Comments**
* GET `/comments/`: all comments
* DELETE `/comments/:id`: delete comment by id

**Posts**
* GET `/posts/`: all posts
* GET `/posts/:id`: get post by ID
* POST `/posts/`: add a post. Body should include `title`, `post_url`, and `user_id`
* PUT `/posts/upvote`: upvote a post. Body should include `post_id`, and `user_id`
* PUT `/posts/:id`: update a post's title. Body should include `title`
* DELETE `/posts/:id`: delete a post by ID
* GET `/posts/`: all posts

**Users**
* GET `/users/`: get all users
* GET `/users/:id`: get user by id
* POST `/users/`: add a user. Body should include `username`, `email`, and `password` (password is hashed with bcrypt)
* POST `/users/login`: validate login credentials. Body should include `email` and `password`
* PUT `/users/:id`: update a user. Body should include any user info you want to update
* DELETE `/posts/:id`: delete a post by ID

## Testing
Test helper functions with `npm test` after cloning the repo and installing dependencies (`npm -i`)

## Packages
- bcrypt
- sequelize
- connect-session-sequelize
- express
- express-handlebars
- express-session
- dotenv
- mysql2

## Questions
If you have questions, email me at [vlane0593@gmail.com](mailto:vlane0593@gmail.com) or reach out on [GitHub](https://www.github.com/vanessalane).
