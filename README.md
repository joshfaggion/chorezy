# Overview
## Name and aliases
The project is named "Chorezy". This is a combination of "chore" and "easy".

## Purpose
The system is designed to make chore chart creation and management incredible easy. Families all over the world have the problem of creating fair and chore charts. We realized this, and with quick research realized their is not a single piece of software that can generate chore charts based on familiy's needs. So, Chorezy was born.

## Technologies
### Chosen
* Ruby on Rails
* Postgres
* REACT
* stimulus.js
* Slim
* Capybara
* RSpec
* Pry
* scss/Bootstrap
* Enzyme

### Tried and rejected
* None yet.

## Technology relationships
This project is using Rails Server Side Rendering to connect the front end of HTML/CSS/JS to the powerful back end server of Ruby/Rails.

## Supported browsers
All modern browsers will be supported.

# How to set up the project
## External tool installation
\```
In Progress
\```

## How to run locally
`rails s`

## How to run tests
`rspec`

# Testing Strategy
## Testing approach
### End User tests
This project applies the concept of TDD and automated testing to create a smooth testing workflow.

### Other tests
Enzyme is being used to test REACT components.

## Continuous integration
Currently, the github repository is using a release branch to encourage collaboration.

# Branching strategy
To begin a new feature run, `git checkout -b <branchname>`.
When finished with the feature and the code has been reviewed, the commits should be squashed before merging.

# Links to:
## [Task management system](http://trello.com)
## [Production](http://chorezy.herokuapp.com)
## External services
* [Heroku](http://herokuapp.com)

# Deployment
## Strategy/process/commands
The release branch is the staging branch. When features are determined that they are ready for production, they will be merged with the master production branch.
