# Curso Básico de GraphQL

## Command for create this project
- `npx license mit > LICENSE && npx gitignore node && git init && npm init -y`

## Commands used for install dependencies
- `npm i graphql`
- `npm i express express-graphql`
- `npm i nodemon -D`
- `npm i standard -D`
- `npm i graphql-tools`
- `npm i dotenv`
- `npm i mongodb`

## Command for create mongodb container with docker
- `docker run -d -p 27017:27017 --name mongodb_platzi -e MONGO_INITDB_ROOT_USERNAME=admin -e MONGO_INITDB_ROOT_PASSWORD=p1a7z1 mongo`
- After that, with Robo 3T (or other tool), create "platzi-cursos" database, "courses" collection and insert some data, example:
```
db.getCollection('courses').insertMany([
  {
    title: 'Mi titulo 1',
    teacher: 'Mi profesor 1',
    description: 'Una descripción 1',
    topic: 'Programación'
  },
  {
    title: 'Mi titulo 2',
    teacher: 'Mi profesor 2',
    description: 'Una descripción 2',
    topic: 'Programación'
  },
  {
    title: 'Mi titulo 3',
    teacher: 'Mi profesor 3',
    description: 'Una descripción 3',
    topic: 'Programación'
  }
])
```

## Command for run
- `npm run dev`

## Commands for linst
- `npm run lint`
- `npm run lint-fix`

## GraphiQL interface URL
- http://localhost:3000/api
