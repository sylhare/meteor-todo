# Meteor todo
[![npm version](https://badge.fury.io/js/meteor-todo.svg)](https://badge.fury.io/js/meteor-todo)

This is a basic todo app with the [meteor platform](https://www.meteor.com/) and [React](https://reactjs.org/).

## Meteor Installation

Following the meteor [installation procedure](https://www.meteor.com/install).

On OSX / Linux:

```bash
curl https://install.meteor.com/ | sh
```

## Starting the app

After installing meteor, go into the `todo-app/` folder then run:

```bash
meteor
```

The the app should be running at [localhost:3000/](http://localhost:3000/).
Once the app is started, you can open a new terminal and manually add a todo item with:

```bash
meteor mongo
```

Then add a new task with:

```bash
db.tasks.insert({ text: "Hello world!", createdAt: new Date() });
```
