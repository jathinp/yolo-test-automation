#Automate tests in Cypress

Pre-requisites:
  - Windows-7 & Above 64bit & memory 4gb minimum
  - Node.js 12 & above
  - IDE (any IDE which supports, used Visual Studio Code)
  
Set Up:
  - Create a new folder for cypress project.
  - Open the folder in VS code
  - Open VS code terminal and run npm init -y [will create a package .json in project folder]
  - Install cypress [npm install cypress]
  - npx cypress verify [To verify the cypress set up]
  - npx cypress open [ To open the cypress]
  - select E2E Testing>>Continue>choose a browser[for ex: firefox]
  - Create new empty spec [can run the default spec (spec.cy.js) as a test run]
 
 POM Script:
  - Create a folder "Pages" [any name can be used as folder name] to capture element in different pages.
  - Create a test json file for game page under above folder "gamespage.js"
  - In json file create a class and add objects , functions and variables [based on the need]
  - Create a test spec in e2e folder "Yolo.cy.js"
  - Import the class in test spec
  - create object for the class
  - call the class functions

 Run script:
 
  - In CLI run command npx cypress run -s .\cypress\e2e\Yolo.cy.js -b firefox  [-s => Spec and -b => Browser] or 
  - Open spec in cypress and run
  

