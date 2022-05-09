# Room-Reservation
A sample project created to implement the DevOps concepts in the reservation of rooms using automation of different tools


## Table of Contents

  * [Table of Contents](#table-of-contents)
  * [Preamble](#preamble)
  * [Project Deadline](#project-deadline)
  * [Project Specification](#project-specification)
  * [Useful Links](#useful-links)
  * [Tenants of Design](#tenants-of-design)
  * [Social Contract](#social-contract)
  * [Branching Strategy](#branching-strategy)

## Preamble

This is the online repository for the "Room-Reservations". Summary of project requirements should go here.

My product will be delivered using an Agile methodology that embraces the DevOps culture. Please note that the culture of this project embraces change and these documents are treated as living, breathing artefacts that will be continuously updated.

  
### Project Deadline
030/06/2022 23:59
  
## Project Specification  

    Clean and simple design
    User access levels (client, administrator)
    Includes at least one self developed api and one webservice
    To be run over Amazon AWS

    Frameworks
    Database
    Database persistence technology
    Define the buisness Requirements
    Named queries and database triggers for security
    Regex for cleansing and validation of data before sending to the database.

## Useful Links

    Jira: https://anup-jacob-jira.atlassian.net/jira/software/projects/RR/boards/1
    GitHub: https://github.com/Anup-Jacob/Room-Reservation.git
    GitWiki: https://github.com/Anup-Jacob/Room-Reservation.wiki.git


## Tenants of Design
    Dedication to clean, secure, performant and self documented code
        code Frameworks to be used
        code coverage tool to be used
        Secure code: Regex for cleansing and validation, Named queries and database triggers
        performance testing tool to be used
    Documentation / code commenting (javadoc)/separate branch
    Datastore for persistance
    Testing:
        Unit testing
        integretation testing
        UA
    Environments:
        staging and production
        tight configuration management for consistency and reproducibility
        automated creation and deployments
        integrated and automated pipeline (commit -> test -> deploy)
    Github version control:
        branches used
        version/release management
    Agile project management methods/principles (jira)
	
## Tools to be used
	
	UI Development - HTML, CSS and Javascript
	Performance testing and monitoring - JMeter
	Unit Testing: Pytest
	Security Testing:	SAST - Snyk
						DAST - StackHawk
	CI Build: Docker using GitHub actions
	Deployments: {Coming soon in AWS EC2}
	Documentation - GitWiki and word documents
	Automated documentation - Sphinx

## Social Contract


## Other

    Jira will be used for task management and planning.

## Branching Strategy.

Main Branch  (Master branch)
	
	-Development Branch
		
		-Feature branches
		.
		.
		.
		
	-Test Branch
	
	-Production Branch

### Estimating Story Points Within Jira

The velocity of my work is calculated by dividing the the number of points burned each sprint divided by no of sprints. The Velocity chart from Jira (below) is used for this calculation.

The teams current story point velocity is "<Choose the number!>".
	
	
	
