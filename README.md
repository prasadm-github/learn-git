# learn-git
		github learning
		


--set username and email

=> git config –global user.email “you@example.com”

=> git config –global user.name “Your Name”


--see config list

=> git config --global --list

--set credential

=> gh auth login

past token


--create new repo and push code

=> echo "# learn-git" >> README.md

=> git init

=> git add README.md

=> git commit -m "first commit"

=> git branch -M main

=> git remote add origin https://github.com/prasadm-github/learn-git.git

=> git push -u origin main

then enter uername and pass(token)

--To reset the commit

=>git reset commit_id (below)