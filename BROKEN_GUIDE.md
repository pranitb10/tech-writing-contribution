# A guide to contribute to open-source repository using git/GitHub:

This document explains how to fork a repository and start working on it. Follow these steps:

2. First Fork repo on GitHUb from the top-right side (dont forget this step is crucial!).

1. clone it to ur lapotp by running folowing comman:
```
git clone https://github/com/username/repo-name.git
```

4. Change your path to the folder where you have cloned the repo:
```
cd into repo-name
```

10. creat a new BRANCH for ur changes (this is required!)
```
git branch -b myFeatureFix
```

3. make change u wants to do in file. add cool feature or remove bugs or do both but dont break code, then add files using below command:
```
git add .
```
#### NOTE: don't forget to save the changes before adding or else you will not push what u change

6. now write commit message and tell what you did:
```
git commt -m "i fixed some issue maybe or not"
```

2. Push to branch but be carefull of name u use:
```
git push -u origin maain
```

7. Then go to your github acount and maked a pull rquest to ask to get code in mainn repo (not ur forked).
