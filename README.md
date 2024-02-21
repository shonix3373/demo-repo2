# github work flow

## local git workflow

Open folder -> cd into folder (cd ../folder name or cd folder name) ->
git init

write code -> git status -> git add . -> git status -> commit changes

# you want to push changes to git hub but the folder is not recognized in git hub yet:

create empty repo in git hub -> copy HTTPS address ->
git remote add origin address
git remote -v (to check if succeeded - will return nothing if not succeeded)
git push -u origin master 



## local development

1. open bla bla bla.

if file is modified (and not created) you can add and commit it at the same time using:
git commit -am "added bla bla"
