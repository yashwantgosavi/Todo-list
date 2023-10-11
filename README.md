# Todo list app
Hosted Link: https://yashwantgosavi.github.io/Todo-list/

### General steps to follow when creating a project
- Thinking about the UI
- Functionality
	- Add a TODO
	- Delete a TODO
	- check task
	- total items count

- Data
	- tasks - an array
	- task - {done, text, id}

- Functions (in code)
    - inputTasks
	- addTask
	- addTaskFromInput
	- addTaskToDOM	
	- markCompletedTask
	- deleteTodo
	- checkTodo
	- renderTodosList
	- showNotification
    - checkList

- input: user will input the todo
			- if user press enter or clicked on add --> todo stored in input arry

- task : if we want to delete or complete any task. we need to know which task is clicked. for that we will generate unique ID for every task, and also true/false case. for storing this data, in js best way is create objects. so I will create new object for everytask 
			- we need to store text in object
			- ID and true/false for completed or uncompleted