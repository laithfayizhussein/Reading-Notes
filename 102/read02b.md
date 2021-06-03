#version control

version control is a system where you can keep updated with each change happend to the file/project 
traking ,comparing,easy solve mistakes,

##version control

Git stores the  data in a file system, you need to' _commit_' every change which help Git keeps your file traked,
the loss of data is rare , becuase of the A-C-P command (git add .,git Commit -m'',git push origin/main),

### Remotes

- view the short names, (example-'origin') using (git remote -v) command,you can find the 'url'  next to the 'short names'.
- add remote using, ('git remot add 'short name' url)
- pull the data you dont have using, ('git fetch [remote name]')
- pushyour changes to the cloud using, '(git push 'remote-name'branch name')'
- Rename using,'(git remote rename)'
- Remove using,'(git remote rm)'



>git fetch solely pulls new data to a local repository; it does not merge changes with or modify your local work. We will discuss merging in a later section. Later, we will also discuss git pull , which allows for fetching and automatic merging.
