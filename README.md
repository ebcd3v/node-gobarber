Backend made with Express.js at Rocketseat GoStack Bootcamp.

# Features
- **[Express](https://github.com/dcodeIO/bcrypt.js)** — JavaScript back-end Framework
- **[JWT](https://github.com/auth0/node-jsonwebtoken)** - JSON Web Token for authentication
- **[bcryptjs](https://github.com/dcodeIO/bcrypt.js)** - Encrypt password for authentication
- **[Redis](https://redis.io/documentation)** — For jobs
- **[Bee Queue](https://github.com/bee-queue/bee-queue)** — Task queue for jobs (uses Redis)
- **[Nodemailer](https://nodemailer.com/about/)** - E-mails
- **[Handlebar](https://handlebarsjs.com/)** - View template (used for e-mails)
- **[PostgreSQ](https://docs.mongodb.com/)** — DB for general data (except notifications and jobs)
- **[MongoDB](https://docs.mongodb.com/)** — DB used for notifications
- **[Sequelize](https://sequelize.org/)** - Used for manipulating SQL DB data
- **[Docker](https://github.com/dcodeIO/bcrypt.js)** — Containers for postgres and redis
- **[Multer](https://github.com/expressjs/multer)** - For file uploads
- **[youch](https://github.com/poppinss/youch)** - Error reporting
- **[Sentry](https://docs.sentry.io/)** - Error monitoring and reporting
- **[yup](https://github.com/jquense/yup)** - Value parsing and validation for requests

# Pre-requisites

- **Node** and **Yarn** installed;
- **Redis** and **PostgreSQL** instances running (Docker containers were used during development);

## ⚡️ Getting started

```
git clone https://github.com/edbrownc/node-gobarber.git
cd node-gobarber
yarn
yarn sequelize db:migrate
yarn sequelize db:seed:all
```

-  After the database has been populated, you may start the api:
```
yarn dev
```
- To start the redis queue, open a new terminal and use:
```
yarn queue
```

