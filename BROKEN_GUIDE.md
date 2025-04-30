# A guide to contribute to open-source repository using git/GitHub:

This document explains how you can fork a repo and start work on it. Please follow these steps:

1. First Fork repo on GitHub from the top-right side (don't forget this step is crucial!).

2. Clone it to your laptop by running following command:
```
git clone https://github/com/username/repo-name.git
```

3. Change your path to the folder where you have cloned the repo:
```
cd repo-name
```

4. Create a new BRANCH for your changes (this is required!)
```
git branch -b myFeatureFix
```

5. Make change you want to do in file. Add cool feature or remove bugs or do both but don't break code, then add files using below command:
```
git add .
```
#### NOTE: don't forget to save the changes before adding or else you will not push what you change

6. Now write commit message and tell what you did:
```
git commit -m "i fixed some issue maybe or not"
```

7. Push to branch but be careful of name you use:
```
git push -u origin main
```

8. Then go to your GitHub account and make a pull request to ask to get code in main repo (not your forked).
