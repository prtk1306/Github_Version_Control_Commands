Note: Don't include '<' '>' in any commands given below.

Install Git version control software
https://git-scm.com/download

After installing Git on your local system, open command prompt, and configure git on your local system
git config --global user.name "GithubUserName"
git config --global user.email <emailId@domain.com>

To clone a repository on your local system
git clone <repositoryURL>

To create a branch of your forked repository (not original repo)

To set your local forked repository as origin for pull requests
git remote set-url origin <YourForkedRepositoryURL>

To create a new branch. Note: branchName could be anything
git checkout -b <branchName>   

To create a pull request
git commit --allow-empty -m "<message>"
git push origin <branchName>

If no errors found in the logs, then simply login to the github account through any browser, navigate to the forked repository, at the top you will find the pull request. Click on the "compare and pull request", change the base repo and submit.





