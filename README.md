# Prisma Quickstart

To replicate the behaviour of Query Console, you can write the Prisma Client queries in the `script.ts` file.

- Run `npm install` to install the dependencies
- Create a `.env` file with a variable called `DATABASE_URL` that contains the connection string to your database.
- Run `npx prisma db pull` to introspect your database schema and populate the `schema.prisma` file.
- Run `npx prisma generate` to generate the Prisma Client.
- Now you can write your queries in `script.ts` and run them with `npm run dev` command. This should replicate the bheaviour of Query Console.
