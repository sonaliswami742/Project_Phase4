# FSD_Phase-4-Project Online Test Application .

DESCRIPTION

The Online Test Application system creates an application that enables users to provide online tests, review them, and display the results.

System Details
This system contains three main modules: Quiz, Review, and Result. The quiz section of the online test application accepts the questions in JSON format. The JSON file can be easily shared from the server in the pre-defined format. The application renders the test at the client-side.
The “Review and display result” section allows users to declare the results immediately. You can simply call another JSON with the answers in it and evaluate and display the results immediately.

![github ss1](https://user-images.githubusercontent.com/95872805/151360183-1e9644a6-e903-4dcd-8609-85a6100cf7d7.png)

Auxiliary concepts:

•	Angular

•	Node js

•	JSON

•	HTML 

•	CSS

•	BOOTSTRAP


About the Project

The quiz application consists of mainly 3 components/views: Quiz View, Review, Result. For the sake of simplicity, I have kept the views in the same file (The result view will be moved to a separate component soon). If you wish to scale this application, you can very well separate these views. Apart from this, quiz.component.ts has been used as a component class for all the views and styles.css has been used to apply CSS style to the application.
