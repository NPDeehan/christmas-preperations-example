# Christmas Preperations Example
This is an example of Camunda orchestrating a process of user tasks and events. 

This example has a BPMN process in which a user can decide to either make cookies or gluhwein. 
Through a series of user task, timers, messages and conditions cookies or gluhwein will be made for guests. 


## How to Deploy. 

Simply open up the model in the Camunda Modeler click the deploy button and select all of the files in the `forms` folder to be deployed with the `.bpmn` model and then deploy to a running instance of the Camunda Engine. 