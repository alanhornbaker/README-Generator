# Professional README Generator

## Motivation for Project

When creating an open source project on GitHub, it’s important to have a high-quality README for the app. This should include what the app is for, how to use the app, how to install it, how to report issues, and how to make contributions—this last part increases the likelihood that other developers will contribute to the success of the project.

Having a README Generator will allow the developer to save time writing the document. The README Generator will also make sure important information isn't missing from the file, and make sure the information is displayed in an accessable, logical way, so that other developers spend less time in confusion when trying to maintain a project.

I am personally building this project because I suck at writing README files, and I find it boring; I want to be spending my time writing code and not drafting explanations, etc. However, as a developer, I want to be easy to collaborate with so that people don't hate working with me.

## Installation and Use

## Errors and Issues

##Ideas for Future Development

1. There is no validate function in the questions array to require the user to provide input.
2. Sometimes it is helpful to have pictures in the README. I would like to add a prompt asking the user for file paths for images they might want to include, prompt for a title, and then have that appear in the generated README.

## How to Contribute

[How to create a Professional README](https://coding-boot-camp.github.io/full-stack/github/professional-readme-guide)

## User Story

AS A developer
I WANT a README generator
SO THAT I can quickly create a professional README for a new project

## Acceptance Criteria

GIVEN a command-line application that accepts user input
WHEN I am prompted for information about my application repository
THEN a high-quality, professional README.md is generated with the title of my project and sections entitled Description, Table of Contents, Installation, Usage, License, Contributing, Tests, and Questions

WHEN I enter my project title
THEN this is displayed as the title of the README

WHEN I enter a description, installation instructions, usage information, contribution guidelines, and test instructions
THEN this information is added to the sections of the README entitled Description, Installation, Usage, Contributing, and Tests

WHEN I choose a license for my application from a list of options
THEN a badge for that license is added near the top of the README and a notice is added to the section of the README entitled License that explains which license the application is covered under

WHEN I enter my GitHub username
THEN this is added to the section of the README entitled Questions, with a link to my GitHub profile

WHEN I enter my email address
THEN this is added to the section of the README entitled Questions, with instructions on how to reach me with additional questions

WHEN I click on the links in the Table of Contents
THEN I am taken to the corresponding section of the README
