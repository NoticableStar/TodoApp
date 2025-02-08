Project: Todo dApp

A todo should have:
    1. integer ide2. string content
    2. string completed
    3. bool completed 
    4. address creator
List of Todos (Array)

Maps:
    address => integer ||| integer will gonna represent the count to todos made by a specific account

Function modifiers:
    onlyCreator()

Functions:
    Write Functions:
    1. createTodo
    2. toggleCompleted
    3. updateTodo
    4. deleteTodo

    Read Functions
    1. getAllTodos
    2. getUserTodos
    3. getTotalTodoCount
