Single Page Web Applications with AngularJS - Setup Env - Che.OpenShift.io.md
-----------------------------------------------------------------------------

# 1 ) Create Workspace on Che.openShift.io:

    a) Go to Your Dashboard Workspace:
https://che.openshift.io/dashboard/#/workspaces

    b) Click Add Wrokspace:

    c) Create NodeJs Express Web Application:
        - You Have two options:
            1. Select "NodeJs Express Web Application - Stack with NodeJS 10"
               Then click "CREATE & OPEN" at the bottom
            2. Seloct Add or Import Project
               Then Select Git Tap
               Then add the Repos Git URL:
https://github.com/che-samples/web-nodejs-sample.git


# 2 ) Git Config:

    a) Set Local User Name/Email:
        - Show user.name / user.email
git config --local user.name
git config --local user.email

        - Setup new user.name / user.email Values:
git config --local user.name "User Name"
git config --local user.email "user@email"

    b) Fork the web-nodejs-sample (Node Express Repo) to your github account :
https://github.com/che-samples/web-nodejs-sample
https://github.com/che-samples/web-nodejs-sample.git

  - Forked 2:
https://github.com/YourGitHubUserName/web-nodejs-sample
https://github.com/YourGitHubUserName/web-nodejs-sample.git

** Change Remote Origin Url on Che IDE Online:
  - Che Dashboard:
https://che.openshift.io/dashboard/#

  - Select Workspace:
  YouOpenShiftID
https://che.openshift.io/dashboard/#/ide/YouOpenShiftID/xXXxToWorkSpaceNamexXxX
https://che.openshift.io/dashboard/#/ide/YouOpenShiftID/n_ex_01-fullstack-course5_-_nodejs-web-app_-_jhu-ep-coursera_fullstack-course5
  - Change Working Directory to nodejs-web-app
cd /projects/nodejs-web-app/

  - Change Origin URL:
git remote set-url origin new.git.url/here
git remote set-url origin https://github.com/new.git.url.here/web-nodejs-sample.git




