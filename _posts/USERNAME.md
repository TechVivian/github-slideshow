---
layout: slide
title: “Welcome to our second slide!”
---
Your test
Use the left arrow to go back!

Step 1: From your project repository, bring in the changes and test.

git fetch origin
git checkout -b xr origin/xr
git merge master
Step 2: Merge the changes and update on GitHub.

git checkout master
git merge --no-ff xr
git push origin master
