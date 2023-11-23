Resources
Read or watch:

Normalizr
Normalizing State Shape
Redux Getting started and core concepts
Redux Actions
Async Actions
Writing tests for Redux
Learning Objectives
At the end of this project, you are expected to be able to explain to anyone, without the help of Google:

Normalizr’s purpose and how to use it
schemas and normalization of nested JSON
core concepts of Redux
Redux actions
Redux action creators
async actions in Redux
how to write tests for Redux
Requirements
Allowed editors: vi, vim, emacs, Visual Studio Code
All your files should end with a new line
All your files will be interpreted/compiled on Ubuntu 18.04 LTS using node 12.x.x and npm 6.x.x
A README.md file, at the root of the folder of the project, is mandatory
Push all of your files, including package.json and .babelrc
All of your functions must be exported
Provided files
notifications.json
Click to show/hide contents of notifications.json


login-success.json
Click to show/hide contents of login-success.json

{
  "first_name": "Johann",
  "last_name": "Salva",
  "email": "johann.salva@holberton.nz",
  "profile_picture": "http://placehold.it/32x32"
}

[
  {
    "id": "5debd76480edafc8af244228",
    "author": {
      "id": "5debd764a7c57c7839d722e9",
      "name": { "first": "Poole", "last": "Sanders" },
      "email": "poole.sanders@holberton.nz",
      "picture": "http://placehold.it/32x32",
      "age": 25
    },
