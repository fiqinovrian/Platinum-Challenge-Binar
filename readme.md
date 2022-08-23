
# Platinum Challenge Binar Bootcamp

This repository contains the Platinum Challenge code from the Binar Academy Bootcamp



## Authors

- [@Fanri Ahmadi](https://github.com/fanri777)
- [@Fiqi Novrian](https://github.com/fiqinovrian)


## Getting Started

Clone my-project with Git

```bash
  git clone my-project
  cd my-project
```
Create .env file

```bash
    # PORT
    PORT=FILLED WITH YOUR PORT
    
    # DATABASE CONFIG
    DB_USER=FILL WITH YOUR USER
    DB_HOST=FILL WITH YOUR DB HOST
    DB_DATABASE=FILL WITH YOUR DATABASE NAME
    DB_PASSWORD=FILL WITH YOUR DATABASE PASSWORD
    
    # NODEMAILER CONFIG
    SMTP_HOST=FILL WITH YOUR SMTP HOST
    SMTP_USER=FILL WITH YOUR SMTP USER
    SMTP_PASSWORD=FILL WITH YOUR SMTP PASSWORD
    SMTP_PORT=FILL WITH YOUR SMTP PORT
    
    # CLOUDINARY CONFIG
    CLOUD_NAME=FILL WITH YOUR CLOUDINARY NAME
    CLOUD_APIKEY=FILL WITH YOUR CLOUDINARY APIKEY
    CLOUD_APISECRET=FILL WITH YOUR CLOUDINARY APISECRET
    
    # HOST
    APP_BASEROUTE= FILL WITH YOUR APP BASE ROUTE

```
Run Create Database and Migrate Database

```bash
    npx sequelize-cli db:create
    npx sequelize-cli db:migrate
```

Install dependencies with npm

```bash
    npm install jest supertest --save-dev
    npm install nodemon --save-dev
```

Start Application

```bash
    npm start
```
    
## Documentation Running On localhost:3000

[Documentation](localhost:3000/docs)

