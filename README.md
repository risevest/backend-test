# Backend Engineer Test

Create an API that serves as an cloud backup system

## Simple Mode
- Users can create an account with:
    - email address
    - password
    - full name
- Users can upload files up to 200mb
- Users can download uploaded files
- Users can create folders to hold files

## Hard Mode
- An admin user type for managing the content uploaded
- Admins can mark pictures and videos as unsafe
- Unsafe files automatically get deleted
- Users can stream videos and audio

## Ultra Mode
- Compression
- File History

## Bonus
- Revokable session management
- Multiple admin reviews before file is deleted

## How to pick what to work on
At minimum you must implement everything in simple mode. You're free to pick and choose what else you
implement along side it. The harder the task, the better your chances. Though make sure to finish the **Simple Mode**
first.

## Tools/Stack

- NodeJs (TypeScript & Express) or Golang
- Postgres for pure data
- Redis
- Docker
- Postman
- S3 or any other shared cloud storage provider

## Tests

Unit tests are a must, submissions without tests will be ignored.


## Time Duration

7 days

## Submission

1. Your API endpoints should be well documented in POSTMAN.
2. Code should be hosted on a git repository, Github preferably.
3. The API should be hosted on a live server (e.g. https://heroku.com)
4. Your app should be `containerized` using `docker`.
5. Share with us through email the:
    - Repository
    - Hosted API URL
    - Postman Collection
    - A list of tasks you did beyond **Simple Mode**