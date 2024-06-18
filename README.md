# FORBES Website README #

## Index
 - [Repository Description](#Repository_Description)
 - [Pre-Requisites](#Pre-Requisites)
 - [Project_Structure](#Project_Structure)
 - [Program_Execution](#Program_Execution)

## Repository Description
This repository contains automated tests for the Forbes Official Website, automating the most important test cases of the web page. 


## Pre-Requisites
 - https://www.oracle.com/java/technologies/downloads/ - Java v.20.0.2
 - https://nodejs.org/en - NPM v.10.8.1
 - https://www.npmjs.com/package/npx NPX v.10.8.1
 - VSCODE Cucumber Extension

## Project_Structure
We are using as POM 


  -  features = "cypress/features" -> This directory contains '.feature' files that describe the web features in a human-readable format. These files use Gherkin syntax.

  -  functions = "cypress/functions" -> This directory can contain helper functions that you can use in your step definitions or anywhere else in your tests.

  -  fixtures = "cypress/fixtures" -> Fixtures are files used to manage and organize test data.

  -  support = "cypress/support" ->  This directory is used to set up global behaviors that apply to all your tests, or to define custom Cypress commands. Also the step_definitions inside contains the files that define the steps used in your '.feature' files. Each step is a function that gets executed when the corresponding step in a '.feature'.

## Program_Execution 
To install al the dependencies after installing pre-requisites:

        - npm i
        
To run the test, open the console and run the command:

        -  npx cypress open