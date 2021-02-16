# MVC-using-Java

## What is MVC?

- It is a Model-View-Controller and the most commonly used architecture.
- MVC helps us to separates the business logic and presentation layer from each other.
- These are the three components used in MVC.

__Model__

- It has business logic and Data State. 
- Getting and manipulating the data, communicates with the controller, interacts with the database, sometimes update the views.

__View__

- The View refers to the xml files.
- It communicates with the controller and sometimes interacts with the model. 
- It passed some dynamic views through the controller.

__Controller__

- The controller handles the business logic.
- It is Activity/Fragment. 
- It communicates with view and model. 
- It takes the user input from view/REST services and Process request Get data from the model and passes to the view.

__Advantages__

- It keeps business logic separate in the model.
- Support asynchronous techniques
- The modification does not affect the entire model.
- Faster development process.

__Disadvantages__

- Due to large code controller is unmanageable.
- Hinders the Unit testing.
- Increased Complexity.
