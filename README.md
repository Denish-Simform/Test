Practical submission for Git Course Test

This test contains total 5 practicals. All the practicals and their commands are mentioned below:

Practical 1: Pull and Merge difference
		- Make example of pull request and two branch merge event.
		
		Steps:
					- Create index file in main branch : touch index.html
					- Perform work on file and commit it : git commit -am "<message>"
					- Edit file and commit it : git commit -am "<message>"
					- Pushed main branch in repo : git push origin main
					- Create feature-1 branch : git checkout -b feature-1
					- Create login.html file in feature-1 and perform work on it : touch login.html
					- Add and commit : git commit -am "<message>"
					- Push feature-1 branch in repo : git push origin feature-1
					- Accept pull request in Hub and merged in repo/main
					- Pull repo/main from hub : git pull origin main
					- Merge change with local repo : git merge
					
					
Practical 2: Rebase
		- Try to rebase feature branch with master branch.
		
		Steps:
					- Create Signup file in main branch : touch singup.html
					- Create and enter into branch-reabse branch : git checkout -b branch-rebase
					- Commit change in signup.html file in branch-rebase branch : git commit -am "<message>"
					- Rebase branch-rebase branch into main branch : git rebase main
					- Rebase main branch into branch-rebase : git checkout main
																									: git rebase branch-rebase
					- Push main branch in repo/main : git push origin main
					
Practical 3: Change commit message
		- Commit push on commit in feature branch and then change commit message.
		
		Steps:
					- Create sub-1 branch : git checkout -b sub-1
					- Create sub.html file in sub-1 and commit : touch sub.html
																											:git commit -am "<message>"
					- Push sub-1 in repo : git push origin sub-1
					- Amend latest commit message : git commit --amend "<amended message>"
					- Push forcely in repo : git push -f origin sub-1
					- Pull repo : git pull origin sub-1
					
			
Practical 4: Cherry pick
		- Pick some commits from feature branch to master branch.
		
		Steps:
					- Edit and Change commit in sub-1 branch : git commit -am "<message>"
					- Copy commit id 
					- Checkout to main : git checkout main
					- Cherrypick commit in main : git cherry-pick <commit-id>
					- Push changes into repo : git push origin main
					
					
Practical 5: Drop commit
		- Remove some commit from feature branch.
		
		Steps:
					- Create drop-commit-branch branch : git checkout -b drop-commit-branch
					- Commit change : git commit -am "<message>"
					- Drop last commit : git rebase -i HEAD^
					- An interactive interface pop-up. Replace "pick" by "drop" in previous commit id. Save and Exit
					- Push changes: git push origin drop-commit-branch
					
					
					
Conclusion : 
					Learnt and hands on various Git commands. Hands on with GitHub UI. 
					

