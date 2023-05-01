[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/Fgxp7zNA)
# Week 3

This week is a deeper dive into advanced MongoDB features. We will practice using these advanced features within a REST API.

## Learning Objectives

At the end of this week, a student should:
- be comfortable using MongoDB for more than simple CRUD operations
- be able to use indexes for performance and uniqueness
- have implemented text search, aggregation, indexes, and lookups 

## The assignment

The assignment this week is designed to get you to use advanced MongoDB functions to solve problems that go beyond basic CRUD. We will use MongoDB as the data source for two sets of CRUD routes within an Express server. We'll then implement more complex APIs that will require advanced Mongo features.

### Getting started

1. Make sure you have a recent version of [Node.js](https://nodejs.org/en/download/) installed on your computer. I am using Node v18.
2. Ensure you have git and github set up on your computer. If you do not, please follow this guide: https://help.github.com/en/github/getting-started-with-github.
3. Clone this repository locally. 
4. In your terminal, from inside this project directory, run `npm install` to install the project dependencies.
5. Download and install [MongoDB](https://www.mongodb.com/try/download/community). This project uses the default MongoDB configuration. If you run Mongo in a non-standard way you may need to update the configuration in `index.js` to match. If you have issues, reference the [Mongoose Connection Guide](https://mongoosejs.com/docs/connections.html).
6. Run `npm start` to start your local server. You should see a logged statement telling you `Server is listening on http://localhost:3000`.
7. Download [Postman](https://www.postman.com/) or an API client of your choice. Browse the various endpoints contained in this project. Practice calling all of them and getting 200 HTTP responses.
8. Run the unit tests of this project: `npm test`. Your test output should end in something like this:
```
Test Suites: 1 failed, 1 passed, 2 total
Tests:       8 failed, 52 passed, 60 total
```

### Your Task

We are working on an API for books and authors. There is a complete set of CRUD routes and tests already provided for these two entities, so you do not need to complete basic CRUD functions.

However, there are a number of tests that are currently failing. Your task is to write the additional route, DAO, and model code that will get these tests passing. Doing so will require the use of the advanced Mongo features we learned about in Week 3, potentially in combination.

Once all the provided tests are passing then you should know your code is correct. You should not make any changes to the test files.


### Grading

Component | Points
--------- | --------
All tests, as originally given, are passing. | 80
Clear, organized project structure | 20

### Submission

- Accept the assignment in Github Classroom
- Github will automatically create a repository for you to complete your assignment in
- Any changes pushed to the main branch of your repository will be a part of your submission
- A Pull Request is automatically created for your submission and will be where you receive feedback
- Continuous Integration is handled using Github Actions. This will automatically run your tests and show the results on your PR. If you see a red X and a message saying `All checks have failed` then you will not receive full credit. Ensure all tests are passing in order to receive full marks. You can see your automated grade output by clicking on the "Checks" tab of your automated Pull Request. Click on the "Node.js CI" check on the left hand side. Now at the bottom of the page you will see a table with your automatic grade already calculated in a table.
- You do not need to do anything else - as long as you've committed to your repo your assignment will be considered submitted.