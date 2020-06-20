# Lab-24 - Class 24

Code 401 Class 24 Routing and Component Composition

## Project Name - RESTy app

Build out the RESTy app, which is a simple clone of Postman. This application should have a few areas of user input, which is then used to make an HTTP request using fetch().

Users should have the following interactable components:

A text input field to enter an API URL
A collection of buttons / A select dropdown to choose which REST method to use (GET, POST, PUT or DELETE)
A submit button that sends the request via HTTP
In this lab, you do not need to provide input fields for users to set their request headers or request body. We will be building upon this application in later labs.

Once the user submits their chosen request, your application should carry out the request and then visually display the response headers and response body to the user. For this lab, you only have to code for APIs that return JSON data in the response body. The response JSON content should be “pretty printed”, or properly tabbed / spaced.

In this *final phase* of the RESTy build, we will be adding some more fidelity to the application, including a menu, history, and an “in-progress” spinner.

The following user stories detail the major functionality for this phase of the project.

* As a user, I want to be able to use all REST methods so that I can do more than just get data
* As a user, I want a simple list of all previous queries I’ve run so that I can easily see which queries I’ve run before
* As a user, I want to click on an old query and have my selections appear in the form for me, so I don’t have to re-type them
* As a user, I want to see all of my previous queries as a separate page so that I can browse them in greater detail
* As a user, I want to see a “loading” indicator while RESTy is fetching data so that I know it’s working on my request


### Author: Sue Duclos

### Links and Resources

- [CodeSandox Link](https://codesandbox.io/s/lab-24-routing-9zv6r?file=/src/App.js)
- [Netlify Deployment](www.abc.com)

### Setup

* npm install
* npm install enzyme
* npm install enzyme-adapter-react-16
* npm start

#### How to initialize/run your application

#### Tests

- npm run test

#### UML

- ![UML24](https://github.com/sueduclos-401-advanced-javascript/lab-22/blob/master/assets/lab-24-uml.png)
