# Lab: "About Me" project

Read the document, in its entirety, before beginning your lab.

## Problem Domain

Teach us more about you! Build out an "About Me" webpage that quizzes the user on fun facts gives the user some basic information about who you are and where you came from. We will build onto this project over the next few labs. Be prepared to refactor your code each day and learn about how a web site incrementally goes from an idea to a deployed site through various iterations of development.

## User Stories

This is our first exposure to user stories. User stories are a device commonly used in software development to identify what the functionality and design of a product should be by considering the interests and motivations of people with varied multiple points of view. They are presented in the manner of

> As a \_\_, I want \_\_, so that \_\_

This layout allows a client to communicate to a team what type of behavior they are looking for and allow the developer team to think up a solution that best fits the the clients need.

The development team will then create sub-bullets called _Feature Tasks_ which are individual tasks that must be completed by the developer to accomplish the user story. Once all of the feature tasks for an individual user story is completed, so is the story.

Below are your lab requirements in this format with the feature tasks already created.

## Instructions

1. As a user, I would like to learn about the site owner so I can get to know them better..
    - Create an About Me guessing game that utilizes HTML, CSS, & JavaScript.
    - Include on your HTML page a short biography, your education history, an overview of your job experience, and any goals that you may have.
    - Prompt the user a total of exactly five yes or no questions.  The user input for the answer must accept either y/n or yes/no responses while taking into consideration case sensitivity by normalizing the user input so that it can be validated (hint: look into the `.toUpperCase()` or `.toLowerCase()` functions). Be sure to let the user know if they answered the question correctly by alerting them with a response.
    - Add `console.log()` messages within your app to notify the user if they are correct. Before submitting, comment out (don't delete) your `console.log()` messages and replace them with the `alerts()` to complete the project.

1. As a user, I would like a personalized welcome message so that I feel like I am interacting with the site owner.
    - Ask the user their name through a `prompt()`
    - Display that name back to the user through a custom greeting welcoming them to your site.
    - Display the user's name back to them in your final message to the user.

1. Using Lighthouse in the Chrome DevTools, analyze the accessibility of your application.
    - The following options to generate a Lighthouse report should be selected:
      - Mode: Navigation
      - Device: Desktop
      - Categories: Accessibility
    - Strive for a score between 50-65. Make necessary adjustments based on the report to achieve that score.
    - Add a screenshot of your score to your README.md file.
