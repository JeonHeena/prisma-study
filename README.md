# prisma-study

This is a repository containing what I studied by referring to the Prisma document.

## Building a REST API with NestJS, PostgreSQL, Swagger and Prisma

_Building the backend REST API for a blog application called "Median"_

Building a backend API with

- TypeScript
- NestJS(version 8)
- PostgreSQL
- Prisma(version 4)

1. Data modeling
2. CRUD (Create, Read, Update, Delete) operations
3. REST API
4. Validtion
5. Error Handling
6. Complex Relations

<NestJS Directory>
- src/app.module.ts : The root module of the application
- src/app.controller.ts : A basic controller with a single route: /. This route will return a simple 'Hello world!' message.
- src/main.ts : The entry point of the application. It will start the NestJS Application.

<start the project>
command
-> npm run start:dev

(This command will watch the files, automatically recompiling and reloading the server whenever I make a change.
To verify the server is running, go to the URL "http://localhost:3000/". and see an empty page with the message 'Hello World!;.)
