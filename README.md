# Deploy-War-on-heroku
Deploy a web application on heroku PaaS



    - install  Heroku Toolbelt from here https://toolbelt.heroku.com/

    - Register on https://heroku.com/ and create a project with name <> on heroku site.

    - Open "Git Bash" - Right click in any directory and open "Git Bash" prompt.

    - Create the postgress database in heroku and provide the DB details in src/main/resources/application.properties

    - Build the project using mvn install, and move to target folder and open the "Git Bash" prompt 

    - Run "heroku deploy:war --war <war file name> --app <application name created on heroku>"

    - Check the Log heroku "logs --tail --app <application name>"

    - Open WSDL https://<application name>.herokuapp.com/ws/
