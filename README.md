# Software Developer Application Test

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


## Authentication and Session Management
1. Use redis as your session store.
3. Authentication and Authorization for admin and user accounts should be done using `Bearer token` and `JWT`.

## Tools/Stack

- NodeJs (TypeScript & Express) or Golang
- Postgres for pure data
- Redis
- Docker
- Postman

## Tests

Unit tests are a must, submissions without tests will be ignored.

## Submission

1. Your API endpoints should be well documented in POSTMAN.
3. Code should be hosted on a git repository, Github preferably.
4. The API should be hosted on a live server (e.g. https://heroku.com)
5. Your app should be `containerized` using `docker`.

## Time Duration

7 days

## NB:

Please send an email to acknowledge the receipt of this document.
