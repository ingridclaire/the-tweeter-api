# Tweeter

Tweeter is a front-end social media application where you can post tweets, comment and like others' tweets and have fun! It is connected to the-tweeter-api, which allows users' tweets and comments to be saved to a database. This is the API for use with the-tweeter-client repo. 

## Client Installation

1. Fork the repo to your github account
2. Clone the repo
3. In your terminal, cd to the directory where you keep projects and run:
```bash
git clone https://github.com/<YOUR-USER-NAME-HERE/the-tweeter-client.git
```
4. Run these commands in the terminal:
```bash
cd the-tweeter-client
npm install
```

## API
| METHOD | ENDPOINT                            | Description             | NOTES                 |
| ------ | ----------------------------------- | ----------------------- | --------------------- |
| GET    | /tweets                             | get all tweets          |                       |
| POST   | /tweets                             | post a tweet            |                       |
| PUT    | /tweets/comments/:id                | add a comment to a tweet| use id of tweet       |
| PUT    | /tweets/likes/:id                   | like a tweet            | use id of tweet       |
| DELETE    | /tweets/comments/:tweetId/:commentId| delete a comment        | use tweet & comment id|
| DELETE | /tweets/likes/:tweetId              | unlike a tweet          | use id of tweet       |
| DELETE | /tweets/:id                         | delete a tweet          |  use id of tweet      |


