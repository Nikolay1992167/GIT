# Description of creating a structure git flow
The project will figuratively describe an example of home renovation.
$ git init. Files created house.txt and README.md. 
$ git add . 
$ git commit -m "feat: start of home renovation" 
$ git tag "v.0.1" - assign tag.
Select a branch 'master'
$ git checkout master
$ git checkout -b "hotfixes" - create new branch 'hotfixes'
Add line 'We bought a house and will be renovating it.' in house.txt
$ git add .
$ git commit -m "fix: severe bug fixed for production"