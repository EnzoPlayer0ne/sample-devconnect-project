# My super cool project

## How to submit example

Let's say this is you repository

```bash
# 1.    fork the main hackerhouse repository
#       go on https://github.com/Internet-Computer-Hackers-Den/devconnect-hackerhouse

# 2.    clone it inside your environment - replace the link with the new fork
cd /tmp
git clone git@github.com:<your new forked url>/devconnect-hackerhouse.git

# 3.    navigate to the cloned repositorycd devconnect-hackerhouse/submissions/
cd devconnect-hackerhouse/submissions/

# 4.    add submodule
git submodule add <URL of your own project> submissions/sample-devconnect-project

# 5.    push the new submodule
git add .
git commit -m "add submission"
git push --set-upstream origin main

# 6.    go to your fork and open a PR
```
