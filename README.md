# Task Manager

A CLI task manager built with Go.

## Add a task
`task add task-name`

Example: 
```
$ task add walk the dog

Added "walk the dog" to your task list.
```

## List all tasks
```task list```

Example: 

```
$ task list                                  

You have the following tasks:
1. Update Readme file
2. Walk the dog
```

## Mark a task as completed
```task do task-number```

Example:

```
$ task do 1

Marked "1" as completed.
```
