# MVC-using-Java

## Architecture pattern

- An architecture pattern gives modularity to the project files and assures that all the codes get covered in Unit testing. 
- It makes the task easy for developers to maintain the software and to expand the features of the application in the future.

## What is MVC?

- It is a Model-View-Controller.
-	The most commonly used architecture. 
-	These are the three components used in MVC -> Model, View and Controller.

__Model__

- It is business logic and Data State. 
- Getting and manipulating the data, communicates with the controller, interacts with the database, sometimes update the views.

__View__

- User Interface consists of XML. 
- It communicates with the controller and sometimes interacts with the model. 
- It passed some dynamic views through the controller.

__Controller__

- It is Activity/Fragment. 
- It communicates with view and model. 
- It takes the user input from view/REST services. 
- Process request Get data from the model and passes to the view.

__Advantages__

- It keeps business logic separate in the model.
- Support asynchronous techniques
- The modification does not affect the entire model.
- Faster development process.

__Disadvantages__

- Due to large code controller is unmanageable.
- Hinders the Unit testing.
- Increased Complexity.
