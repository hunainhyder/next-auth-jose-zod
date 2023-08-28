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
