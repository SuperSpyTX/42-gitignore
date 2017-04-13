# 42-gitignore

These are .gitignore files for [42's](https://42.us.org) C Piscine.  During the piscine, these files will make certain git commands a lot easier instead of 
having to remember the files to turn in for each project.  This should make repositories on vogsphere a lot
cleaner and only have the files needed to be turned in.

## Instructions

Copy one of these files off this gist (< Command >< C >) (according to which project) and save it as ```.gitignore```

- **Make sure you're in the parent directory of all the exercises (or where .git exists!) - use cd otherwise!**
- ```nano .gitignore```
- < Command >< V >
- Save the file (CTRL + X, hit Y, hit Enter)

Now you can run ```git add .``` without git adding additional files that you don't need.

**If you have already had committed files prior to adding .gitignore, run ```git rm -r --cached .``` to remove the files from git itself, then run ```git add .```.  The files that are supposed to be submitted at that time will be added.**

## Contributors

Thanks to the following for making .gitignores when I couldn't:
- [@AlexEzzeddine](https://github.com/AlexEzzeddine), [@logankaser](https://github.com/LoganKaser), @amittal

_If you have a GitHub account, please let me know and I'll update this repository with it._ 
