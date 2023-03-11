# ASB-2
  
Cancel CircleCI CI execution without including `[skip-ci]` in commit message.  
  

1. `git commit -m "xxx"`  
2. `git notes add -m "[skip-ci]"`  
3. `git push origin refs/notes/commits`
4. `git push origin head`
