# Strapi Mysql Starter

Just a 2020 template ready to use with:

- strapi 3.0.1
- mysql


# Requirements
- Nodejs ≥ 10
- Mysql database. You could use this docker snippet https://gist.github.com/jrichardsz/73142c5c7eb7136d80b165e75d3a1e22

# Start strapi

- Create a database inside mysql instance. Name will be required in the next steps
- Import the required tables and data: ./database/database.sql
- Export or configure this environment variables

```sh
export PORT=1337
export DATABASE_HOST='127.0.0.1'
export DATABASE_PORT=3306
export DATABASE_NAME='some_database'
export DATABASE_USERNAME='root'
export DATABASE_PASSWORD='123456789'
export DATABASE_SSL=false
```

> Configure this variables in heroku web panel

- execute:

```sh
npm run start
```
