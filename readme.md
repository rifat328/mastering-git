
## Mastering Git 


- added Branch
  -- Git init --
  move head to that point

<!-- git checkout 16c5410f9654b2cb392c31ef14aa23693a0e8243  -->

<!-- git checkout main  move head to latest commit -->
<!-- do the same  git checkout -f main -->

<!-- git remote add origin [repo location]
    here origin can be something else with dif repo loction
    like git remote add something [repo location/ clone link]
    you can also push to  diff branch location
like git push origin main or
    git push something main
does the same for diff repo location

new branch   =>  git branch branch name -->

create new Branch ==> git branch secondery-branch

        switching between different branch

git checkout secondery-branch
git checkout main

creating a branch and immidiate move onto it
git checkout -b testingTeam

make a branch not under main branch but a specified branch of an branch
git branch testingTeam2 testingTeam
here testingTeam2 is a new branch of testingTeam

git push --set-upstream origin testingTeam2
remote origin => branch Name
git push -u origin testingTeam2 set a tracking relation ship
git pull to up to date
