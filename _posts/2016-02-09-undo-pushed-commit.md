---
layout: post
title: Undo pushed commit
published: true
---
  
  
```bash
git reset --hard HEAD~1  
git push -f <remote> <branch>
```

This will undo the last commit and push the updated history to the remote. You need to pass the -f because you're replacing upstream history in the remote.

[_Source_](http://stackoverflow.com/questions/6459080/how-can-i-undo-a-git-commit-locally-and-on-a-remote-after-git-push)
