## About
Strapi latest in docker using docker compose  
Dockerize with [@strapi-community/dockerize](https://github.com/strapi-community/strapi-tool-dockerize)  

## What I did
```
C:\workspace\strapi4-dockerize-boilerplate>npx create-strapi-app@latest
Need to install the following packages:
create-strapi-app@4.5.5
Ok to proceed? (y) y
? What would you like to name your project? my-strapi-project
? Choose your installation type Custom (manual settings)
? Choose your preferred language
? Choose your preferred language TypeScript
? Choose your default database client
? Choose your default database client postgres
? Database name: (my-strapi-project)
? Database name: my-strapi-project
? Host: (127.0.0.1)
? Host: 127.0.0.1
? Port: (5432)
? Port: 5432
? Username: strapi
? Username: strapi
? Password: ******
? Password: ******
? Enable SSL connection: (y/N) y
? Enable SSL connection: Yes

Creating a project with custom database options.
Creating a new Strapi application at C:\workspace\strapi4-dockerize-boilerplate\my-strapi-project.
Creating files.
Dependencies installed successfully.

Your application was created at C:\workspace\strapi4-dockerize-boilerplate\my-strapi-project.

Available commands in your project:

npm run develop
Start Strapi in watch mode. (Changes in Strapi project files will trigger a server restart)

npm run start
Start Strapi without watch mode.

npm run build
Build Strapi admin panel.

npm run strapi
Display all available commands.

You can start by doing:

cd C:\workspace\strapi4-dockerize-boilerplate\my-strapi-project
npm run develop

C:\workspace\strapi4-dockerize-boilerplate>cd my-strapi-project

C:\workspace\strapi4-dockerize-boilerplate\my-strapi-project>npx @strapi-community/dockerize

 @strapi-community/dockerize  v1.9.1 by Simen Daehlin    
Easy add docker support for a Strapi Project
https://github.com/strapi-community/strapi-tool-dockerize

🎉  You, and 768 other people have used this tool this month

🍿  TypeScript project detected

📦  NPM detected

√ Do you want to create a docker-compose file? 🐳 ... No / Yes
√ What environments do you want to configure? » Development
√ Whats the name of the project? ... my-strapi-project
√ What database do you want to use? » PostgreSQL
√ Database Host ... 127.0.0.1
√ Database Name ... strapi
√ Database Username ... strapi
√ Database Password ... ******
√ Database Port ... 5432
🐳  Added docker-compose file with POSTGRESQL configuration

🕵️   Added  Dockerize variables in .env

💾  Added POSTGRESQL configuration to database.ts 

📦  Cleaned up old dependencies

📦  POSTGRESQL dependencies installed with NPM 

🐳  Dockerfile for DEVELOPMENT added

⭐️  Star the project on GitHub if you liked this tool 🙏 

🎉  We now have got 152 🌟 and counting... 

👉  https://github.com/strapi-community/strapi-tool-dockerize 👈


C:\workspace\strapi4-dockerize-boilerplate\my-strapi-project>
```

## Usage
```
C:\workspace\strapi4-dockerize-boilerplate\my-strapi-project>docker compose up
```
