# Developing Cloud Apps with Node.js and React - IBM Full Stack Cloud Developer Specialization

## Final Project Overview

The final project for this course has several steps that you must complete. To give you an overview of the whole project, all the high-level steps are listed below. The project is then divided into several smaller labs that give the detailed instructions for each step. You must complete all the labs to successfully complete the project.

## Project Breakdown

**Pre-work: Sign up for IBM Cloud account and create a Watson Natural language Understanding service**

1. Create an IBM cloud account if you don't have one already.
2. Create an instance of the Natural Language Understanding (NLU) service.

**Part A: Fork the Git repository to have the server and client code you need to start**

1. Create your own copy of the git repository which has the code you need to build up on.
2. Clone the repository into the `theia` environment

**Part B: `npm` install the necessary packages**

1. Change to the React client directory (`sentimentanalyzeClient`) and install all the packages required in your local environment for the React application to run.
2. Change to the express JS server directory (`sentimentAnalyzeServer`) and install all the packages required in your local environment for the server to run.

**Part C: Install IBM Watson package and set up the .env file**

1. Install the `ibmwatson` package in your server and create `.env` file to add the credentials to point to your Watson NLU credentials, in the `sentimentAnalyzeServer` directory.
2. Make changes in sentimentAnalyzerServer.js to create an instance of `NaturalLanguageUnderstanding` using the credential from the `.env` file using `dotenv` package.

**Part D: Create endpoints to cater to the URL and text input from the React client**

1. Create four different end points each of which can use the same instance of NLU
2. Run the server and the React application to see if the desired output is displayed
3. Render the analysis from the server color formatted depending on the sentiment analyzed.
4. Render the confidence level of all the emotions in the text or `url` sent.
