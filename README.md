# Description of creating a structure git flow
The project will figuratively describe an example of home renovation.
$ git init. Files created house.txt and README.md. 
$ git add . 
$ git commit -m "feat: start of home renovation" 
$ git tag "v.0.1" - assign tag.
$ git checkout -b develop - create a branch 'develop'
Add line '1. We are repairing the roof.' in house.txt.
$ git add .
$ git commit -m "feat: task to repair the roof"
Add line '2. We are repairing the walls.' in house.txt.
$ git add .
$ git commit -m "feat: task to repair the walls"
Add line '3. Yard landscaping.' in house.txt.
$ git add .
$ git commit -m "feat: task of landscaping the yard"
Select commit 'db60945' in branch 'develop'
$ git checkout -b feature/pool - create a branch 'feature/poll'
File created pool.txt and added line '1. Install a swimming pool.'
Add line '2. Install an umbrella.' in pool.txt.
$ git add .
$ git commit -m "feat: task to install an umbrella"
Add line '3. Install sunloungers.' in pool.txt.
$ git add .
$ git commit -m "feat: task to install sunloungers"