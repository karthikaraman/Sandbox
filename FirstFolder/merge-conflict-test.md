Test file to see the effects of working in multiple branches with git pull origin:newbranch command vs. git checkout branch syntax.

This first line was created a new working branch that was created with git pull origin master:workingbranch

The second sentence was created on a workingrelease branch that was also created using the git pull origin originreleasebranch:newworkingreleasebranch

The third sentence was created on the workingmaster branch that was created using git checkout -b

This one was created on working release that was created with checkout -b from master and then updated with pull originrelease
