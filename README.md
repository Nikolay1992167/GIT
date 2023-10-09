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
$ git checkout -b feature/garden
Create garden.txt and add line '1. Plant fruit trees.'
$ git add .
$ git commit -m "feat: task to plant fruit trees"
Add line '2. Plant berry bushes.' in garden.txt
$ git add .
$ git commit -m "feat: task to plant berry bushes"
Add line '3. Plant strawberries.' in garden.txt
$ git add .
$ git commit -m "feat: task to plant strawberries"
Add line '4. Plant raspberries.' in garden.txt
$ git add .
$ git commit -m "feat: task to plant raspberries"
Select a branch 'develop' 
$ git checkout develop
Add line '4. We are repairing the floor.' in house.txt.
$ git add .
$ git commit -m "feat: task to repair the floor"
Select a branch 'master'
$ git checkout master
$ git checkout -b "hotfixes" - create new branch 'hotfixes'
Add line 'We bought a house and will be renovating it.' in house.txt
$ git add .
$ git commit -m "fix: severe bug fixed for production"
Select a branch 'develop'
$ git checkout develop
Merge branch 'hotfixes' into branch 'develop'
$ git merge --no-ff hotfixes
Go to state 'develop|MERGING' and resolve conflicts in files house.txt and README.md
$ git add .
$ git commit -m "Merge branch 'hotfixes' into branch 'develop'"   
Select commit 'db60945' in branch 'develop'
$ git checkout -b feature/pool - create a branch 'feature/poll'
File created pool.txt and added line '1. Install a swimming pool.'
Add line '2. Install an umbrella.' in pool.txt.
$ git add .
$ git commit -m "feat: task to install an umbrella"
Add line '3. Install sunloungers.' in pool.txt.
$ git add .
$ git commit -m "feat: task to install sunloungers"
Select a branch 'develop'
$ git checkout develop
Merge branch 'feature/pool' into branch 'develop'
$ git merge --no-ff feature/pool
Go to state 'develop|MERGING' and resolve conflict in file README.md
$ git add .
$ git commit -m "Merge branch 'feature/pool' into branch 'develop'"
$ git checkout -b release - create new branch 'release' 
File created address.txt and add line 'Republic of Belarus'
$ git commit -m "feat: add address"
Add line 'Mozyr, Geologov street, 15' in address.txt
$ git add .
$ git commit -m "fix: updated address"
Select a branch 'release'
$ git checkout release
Add line 'Postcode: 247795' in address.txt.
$ git add .
$ git commit -m "fix: fixed address add postcode"
Add line 'Gomel region' in address.txt.
$ git add .
$ git commit -m "fix: fixed address add region'