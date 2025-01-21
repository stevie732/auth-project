# Project
- Authentication Application.

## 1 - Initialize App.
- `npm init`
  * set author.
  * set index.js
  * leave all else empty.

- create index.js file.

## 2 - Install Dependencies.
- `npm` install the commands below.
  * `bcryptjs`
  * `cookie-parser`
  * `cors`
  * `express`
  * `helmet`
  * `joi`
  * `jsonwebtoken`
  * `mongoose`
  * `nodemailer`

## 3 - Updates.
- Update `package.json` file.
  * delete `test`.
  * add `"start": "node --env-file=.env index.js"`.
  * add `"dev": "node --watch --trace-warnings --env-file=.env index.js"`.

## 4. Create `.env` file.