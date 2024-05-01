
1.	installing the GIT 
	Download Git: Go to https://git-scm.com/download/win and get the Git installer for Windows.
	Run Installer: Double-click the downloaded file to start the installation process.
	Follow Instructions: The installer will guide you through the process with simple prompts. Just click "Next" or "Install" as appropriate.
	Choose Options: During installation, select "Use Git from the Windows Command Prompt" so you can run Git commands from the Command Prompt or PowerShell easily.
	Finish Installation: Once the installation completes, click "Finish".
	Check Installation: Open Command Prompt or Git Bash and type git --version to make sure Git is installed correctly. You should see the installed version displayed.

2.	manage public and private repository
	Create a Repository: If you haven't already, create a repository on GitHub. Sign in to your GitHub account, click on the "+" icon in the top right corner, and choose "New repository". Fill in the necessary details like repository name, description, etc., and click "Create repository".
	Access Repository Settings: Once your repository is created, navigate to its main page. You'll see options like "Code", "Issues", "Pull requests", etc. Click on the "Settings" tab located near the top-right corner of the repository page.
	Change Repository Visibility: In the Settings page, scroll down until you find the "Danger Zone" section.
	Under "Danger Zone", you'll find the "Change repository visibility" option.
	Click on "Change repository visibility" and select "Private" from the dropdown menu.
	Confirm Changes: After selecting "Private", GitHub will prompt you to confirm the change. You might need to provide your GitHub password or re-enter your account credentials to confirm the action.
	Save Changes: Once confirmed, click on the "Make private" button to save your changes.
	Verify Repository Status: After making the repository private, its visibility will be updated accordingly. You'll notice a lock icon next to the repository name, indicating that it's now private.


3.	Write and execute the commands to set up and configure git on your local machine. 


![image](https://github.com/URK23CS1144/project-2/assets/153486547/bcc5f8f8-7f88-404c-be48-be615ef275c8)
![image](https://github.com/URK23CS1144/project-2/assets/153486547/4992bd0d-a9cc-455b-ad13-1142ce4877ef)
![image](https://github.com/URK23CS1144/project-2/assets/153486547/610062fb-3a32-4214-a588-428fedd3f322)



4.	performing basic operations in Git. 
![image](https://github.com/URK23CS1144/project-2/assets/153486547/04298bf6-b5e0-476f-baba-ad63dd6ccbd5)
![image](https://github.com/URK23CS1144/project-2/assets/153486547/5e82cc21-a20c-40b3-94c9-774912336ba4)



5.	Write and execute the three important steps of version control. 
![image](https://github.com/URK23CS1144/project-2/assets/153486547/972460b6-7090-4798-9206-1a540cb2935b)
![image](https://github.com/URK23CS1144/project-2/assets/153486547/82a2232a-522f-47b0-87ce-65ae8e100fb3)
![image](https://github.com/URK23CS1144/project-2/assets/153486547/14cfd8bd-4fbb-4f21-b3f9-530c7e8168ae)





6.	execute git add, git commit, git push, git pull, git status.
11.![image](https://github.com/URK23CS1144/project-2/assets/153486547/c43660b8-a55e-42f0-98e9-ce846ceaa458)
12.![image](https://github.com/URK23CS1144/project-2/assets/153486547/218f3c19-6895-42b9-8814-fa559b631380)
13.![image](https://github.com/URK23CS1144/project-2/assets/153486547/fcf957e3-0df7-4d81-ab5d-e88ec162134f)
14.![image](https://github.com/URK23CS1144/project-2/assets/153486547/2546bc65-bbe9-4c53-9e2e-913d44279fd6)
15.![image](https://github.com/URK23CS1144/project-2/assets/153486547/d415ac11-d490-4dee-b0a6-9bb5573f2700)



   
7.	Explain and execute how to create branches and merging branches. 
Creating branches
To keep track of changes to this file using git, you need to:
1.	Clone the repository.
2.	Move into the cloned repository
3.	Create a new branch using the command (replace feature-branch with your desired branch name).
git checkout -b feature-branch
4.	Make modifications to files in your project.
5.	Use git add to add the changes to the staging area
6.	Commit the changes with a meaningful message

Merging branches
To keep track of changes to this file using git, you need to:
1.	Switch back to the main branch.
git checkout main
2.	Merge the branch into the main branch
git merge feature-branch
3.	Resolve conflicts (if necessary)
i.	Open the conflicting files and resolve the conflicts manually.
ii.	After resolving conflicts, add the changes to the staging area and commit:
git add .
git commit -m "Merge feature-branch into main"
4.	Push changes to github using the following command.
git push origin main




8.Create and Address GitHub Issues

1.	Create a new issue in your repository:
i.	Go to your GitHub repository.
ii.	Click on the "Issues" tab.
iii.	Click the "New issue" button.
iv.	Fill in the issue title and description.
v.	Optionally, assign the issue to a collaborator, apply labels, and set milestones.
2.	Assign the issue to a collaborator:
i.	Within the issue, use the "Assignees" section to assign the issue to a collaborator.
ii.	The assigned collaborator will receive notifications about the issue.
3.	Label the issue with appropriate tags:
i.	Apply labels to categorize and prioritize issues.
ii.	Create and use labels like "bug," "feature," or any relevant labels for your project.
iii.	Labels can be added when creating the issue or edited later.
4.	Close the issue using a commit message:
i.	Make changes to the codebase to address the issue.
ii.	In your local repository, commit the changes with a commit message that references the issue number:
git commit -m "Fix #1: Resolve issue with feature X"
Replace "1" with the actual issue number.
iii.	Push the changes to GitHub:
git push origin main
The issue will be automatically closed when the commit is pushed.




