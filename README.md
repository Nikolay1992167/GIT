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