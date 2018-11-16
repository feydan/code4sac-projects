# code4sac-projects
A listing of projects and resources for Code4Sac

## Councilmatic

Councilmatic is a web application that pulls information about bills, representatives, and events from the city and displays it in an easy to consume way for anyone looking for this information.

Champion: Dan Fey (https://github.com/feydan)

Help needed:
- Python experience
- Devops/Docker experience

Resources:
There are three projects that need to be hosted together and configured to interact
1. https://github.com/opencivicdata/scrapers-us-municipal/pull/243 - Scrapers pull information from the City of Sacramento's Legistar site and save it into a Postgres Database
2. https://github.com/opencivicdata/imago - Open Civic Data (OCD) Api pulls from the Postgres Database and publishes the information via API
3. https://github.com/datamade/councilmatic-starter-template - Pulls the data from the OCD Api, saves it into a Postgres database, and displays the information -- this is the councilmatic web application and front-end.  There's a Sacramento fork, but it may need updating: https://github.com/code4sac/sacramento-councilmatic

PR for Sacramento Changes: https://github.com/opencivicdata/scrapers-us-municipal/pull/243

## BankON Sacramento

Bank On’s goal is to ensure that everyone has access to a safe and affordable bank or credit union account.  This project is building a map of branches that offer these accounts to be displayed on United Way's website.  We'd like this for Sacramento, but it would be great to support mapping nation wide.

Champion: Needed

Help Needed:
- Champion
- Javascript experience

Resources:
https://github.com/sfbrigade/SFOFE-BankOn

## OpenBudgetSac

Displays city budgetary information and allows exploration of the data.  We have one application in the project updated with the new data, but the other applications need to be updated as well.

Champion: Needed

Help Needed:
- Champion
- Javascript experience

Resources:
https://github.com/code4sac/openbudgetsac.org
