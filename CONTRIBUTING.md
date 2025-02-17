# Contributing Guidelines
This documentation contains set of guidelines to help you during the contribution process.

# Submitting Contributions👨🏻‍💻
Below you will find the process and workflow used to review and merge your changes.

##  Step 1 : Choose an issue/ Create an issue
- Look for the existing issue or create your own issue.
- Comment on the respective issue you would like to work before creating a Pull Request.
- Wait for the issue to be assigned to you after which you can start working on it.

## Step 2 : Fork the repository
- Fork this repository by clicking on the "Fork" button. This will create a local copy of this repository on your GitHub profile.

## Step 3 : Clone the forked repository
- Once the repository is forked you need to clone it to your local machine.
- Click on the "Code" button in the repository page and copy the link provided in the dropdown menu.

```bash
git clone https://github.com/<your-username>/<repo-name>  
```
- Keep a reference to the original project in `upstream` remote.

```bash  
cd <repo-name>  
git remote add upstream https://github.com/<upstream-owner>/<repo-name>
git remote -v # To the check the remotes for this repository 
```  
- If the project is forked already, update the copy before working.

## Step 4 : Fetch and merge upstream changes
- Before working on your issue, it is important to fetch the latest changes from the original repository.

```bash
git remote update
git checkout <branch-name>
git rebase upstream/<branch-name>
``` 

## Step 4 : Create a new branch
- Always create a new branch and name it accordingly so as to identify the issue you are addressing.

```bash
# It will create a new branch with name branch_name and switch to that branch 
git checkout -b branch_name
```
## Step 5 : Work on the issue assigned
- Work on the issue(s) assigned to you, make the necessary changes in the files/folders needed.
- After making the changes add them to the branch you've created.

```bash  
# To add all new files to branch Branch_Name  
git add .  
# To add only a few files to Branch_Name
git add <file name>
```
## Step 6: Commit the changes
- Add your commits.
- Along with the commit give a descriptive message that reflects your changes.

```bash
git commit -m "message"  
```
- Note : A Pull Request must have at least one commit. 

## Step 7: Push the changes
- Push the committed changes in your branch to your remote repository.

```bash  
git push origin branch_name
```

## Step 8: Create a Pull Request
Once you are done with your work, create a pull request by clicking on the "New Pull Request" button.

Click the "Create pull request" button in the "New Pull Request" page.
Provide a descriptive title for your pull request that reflects the changes you've made.
In the compare and pull request section of your repository, select the branch you created and the main branch of the repository.

## Step 9: Add Details to Your Pull Request
Click on the "Edit" tab in your pull request page.
Add a title and description that best describes your contribution. Screenshots can be added here as well to help the maintainer understand what changes are being made.

## Step 10: Wait for Review
Once your Pull Request gets approved, it will get merged into the original code base by the contributor or maintainer.

## And...: Celebrate
Congratulations! You have successfully contributed to the project and made a valuable contribution to the community.

## Step 11: Learn from the experience
After contributing to a project, you can learn a lot about how to contribute effectively and improve your skills as a developer. You can also use this experience to improve your communication skills with other developers in the community.

## Step 12: Keep contributing
Contributing to open-source projects is a great way to learn new skills and improve your problem-solving abilities. You can continue to contribute to other projects in the community by following the same steps as above.

## Step 13: Be patient
Contributing to open-source projects can take time and effort. It's important to be patient with yourself and not get discouraged if you don't see immediate results.

## Step 14: Be respectful
When contributing to open-source projects, it's important to be respectful and considerate of other developers' opinions and contributions. It's also important to follow the project's guidelines and coding standards.

## Step 15: Be persistent
Contributing to open-source projects can be a challenging task, but it's important to be persistent and keep working towards your goals. It's also important to stay committed to the project and not give up on your contributions.

## Step 16: Be open-minded
Open-source projects are a great way to learn new skills and improve your problem-solving abilities. You can continue to contribute to other projects in the community by following the same steps as above.

## Step 17: Be proactive
Contributing to open-source projects can be a great way to learn new skills and improve your problem-solving abilities. You can continue to contribute to other projects in the community by following the same steps as above.
