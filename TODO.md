# Things to do!

## Config
[x] install auth 
[x] install logger
[x] install saga
[x] install axios

## Client
[ ] auth - login
[ ] to-do list component
[ ] projects component
[ ] MUI?
[ ] Sagas
    [ ] _Root
    [ ] Todo.Saga.ts
        [ ] fetchTodos
        [ ] addTodo
        [ ] deleteTodo
        [ ] updateTodo
        [ ] fetchTodo
    [ ] Project.Saga.ts
        [ ] fetchProjects
        [ ] fetchProject
        [ ] addProject
        [ ] deleteProject
        [ ] updateProject
[ ] Reducers
    [ ] _Root? am I using toolkit or nah? 
    [ ] Todo Reducer
    [ ] Todos Reducer
    [ ] Projects Reducer
    [ ] Project Reducer

## Server
[ ] user router
    [ ] I don't know if I even need a user router because of Auth0 - let's find out!!
[ ] todo router
    [ ] GET - single todo :id 
    [ ] GET - all todos :project_id
    [ ] POST
    [ ] DELETE :id 
    [ ] PUT :id 
    [ ] route for deleting multiple? would this just be a saga that hits the server multiple times? look into it!
[ ] project router
    [ ] GET - single project :id
    [ ] GET - all projects :owner 
    [ ] POST
    [ ] DELETE :id
    [ ] PUT :id 

## DB
[x] create tables
[ ] link db to server

