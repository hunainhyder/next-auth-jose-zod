# Next.js 13 Authentication System
Next.js 13 Authentication system using JSON Web Tokens

> Libraries used
- Zod - For Validation Schema
- Jose - For generating and verifying JWT tokens
- Bcryptjs - For hashing passwords

> How to run

First clone the repo or download code then open the folder in ternimal.

Then run the following commands 
```
npm i -g pnpm
pnpm i
npx prisma migrate dev --name init
```
After running these commands your authentication api will be ready to use

Use this command to run the api
```
pnpm run dev
```

> Testing the API

You can test this API in postman

- First run the API using `pnpm run dev` command
- Then in Postman go to `/api/auth/register` endpoint and send new user registeration data in request body using POST method.
- Then in Postman go to `/api/auth/login` endpoint and send user data to login in request body using POST method.
- Then in Postman go to `/api/users/me` endpoint to get current logged in user details using GET method.
- Then in Postman go to `/api/auth/logout` endpoint to logout using GET method.

Sample Test Images

