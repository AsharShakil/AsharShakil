- 👋 Hi, I’m @AsharShakil
- 👀 I’m interested in data science
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...

<!---
AsharShakil/AsharShakil is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
https://youtu.be/apGV9Kg7ics?si=LB_VJ1EyJJMKlP8b
Last login: Sat Mar 16 12:11:24 on console
devvalecha@Devs-Air ~ % cd 
devvalecha@Devs-Air ~ % ls
Applications	Documents	Library		Music		Public
Desktop		Downloads	Movies		Pictures
devvalecha@Devs-Air ~ % cd Desktop
devvalecha@Devs-Air Desktop % ls
HR database Dashboard.pbix	mac
aws-sdk-js
devvalecha@Devs-Air Desktop % git init
hint: Using 'master' as the name for the initial branch. This default branch name
hint: is subject to change. To configure the initial branch name to use in all
hint: of your new repositories, which will suppress this warning, call:
hint: 
hint: 	git config --global init.defaultBranch <name>
hint: 
hint: Names commonly chosen instead of 'master' are 'main', 'trunk' and
hint: 'development'. The just-created branch can be renamed via this command:
hint: 
hint: 	git branch -m <name>
Initialized empty Git repository in /Users/devvalecha/Desktop/.git/
devvalecha@Devs-Air Desktop % git add HR database Dashboard.pbix
fatal: pathspec 'HR' did not match any files
devvalecha@Devs-Air Desktop % cd Hr
cd: no such file or directory: Hr
devvalecha@Devs-Air Desktop % ls
aws-sdk-js	hr dashboard	mac
devvalecha@Devs-Air Desktop % cd hr dashboard
cd: string not in pwd: hr
devvalecha@Devs-Air Desktop % cd        
devvalecha@Devs-Air ~ % ls
Applications	Documents	Library		Music		Public
Desktop		Downloads	Movies		Pictures
devvalecha@Devs-Air ~ % cd Desktop
devvalecha@Devs-Air Desktop % ls 
aws-sdk-js	hr dashboard	mac
devvalecha@Devs-Air Desktop % cd hr dashboard
cd: string not in pwd: hr
devvalecha@Devs-Air Desktop % cd hr dashboard       
cd: string not in pwd: hr
devvalecha@Devs-Air Desktop % ls
aws-sdk-js	hr dashboard	mac
devvalecha@Devs-Air Desktop % ls
aws-sdk-js	hdashboard	mac
devvalecha@Devs-Air Desktop % cd hdashboard
devvalecha@Devs-Air hdashboard % ls
HR database Dashboard.pbix
devvalecha@Devs-Air hdashboard % git init
hint: Using 'master' as the name for the initial branch. This default branch name
hint: is subject to change. To configure the initial branch name to use in all
hint: of your new repositories, which will suppress this warning, call:
hint: 
hint: 	git config --global init.defaultBranch <name>
hint: 
hint: Names commonly chosen instead of 'master' are 'main', 'trunk' and
hint: 'development'. The just-created branch can be renamed via this command:
hint: 
hint: 	git branch -m <name>
Initialized empty Git repository in /Users/devvalecha/Desktop/hdashboard/.git/
devvalecha@Devs-Air hdashboard % ls      
HR database Dashboard.pbix
devvalecha@Devs-Air hdashboard % ls
HR-database-Dashboard.pbix
devvalecha@Devs-Air hdashboard % git add HR-database-Dashboard.pbix
devvalecha@Devs-Air hdashboard % git status
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
	new file:   HR-database-Dashboard.pbix

devvalecha@Devs-Air hdashboard % git commit -m "uploading hr file"
[master (root-commit) fd66005] uploading hr file
 Committer: Dev Valecha <devvalecha@Devs-Air.zyxel.box>
Your name and email address were configured automatically based
on your username and hostname. Please check that they are accurate.
You can suppress this message by setting them explicitly. Run the
following command and follow the instructions in your editor to edit
your configuration file:

    git config --global --edit

After doing this, you may fix the identity used for this commit with:

    git commit --amend --reset-author

 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100755 HR-database-Dashboard.pbix
devvalecha@Devs-Air hdashboard % git remote add origin https://github.com/AsharShakil/hr_dashboard.git
devvalecha@Devs-Air hdashboard % git push -u origin main
error: src refspec main does not match any
error: failed to push some refs to 'https://github.com/AsharShakil/hr_dashboard.git'
devvalecha@Devs-Air hdashboard % git push
fatal: The current branch master has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin master

To have this happen automatically for branches without a tracking
upstream, see 'push.autoSetupRemote' in 'git help config'.

devvalecha@Devs-Air hdashboard % git origin
git: 'origin' is not a git command. See 'git --help'.
devvalecha@Devs-Air hdashboard % git remote -v
origin	https://github.com/AsharShakil/hr_dashboard.git (fetch)
origin	https://github.com/AsharShakil/hr_dashboard.git (push)
devvalecha@Devs-Air hdashboard % git push -u origin main
error: src refspec main does not match any
error: failed to push some refs to 'https://github.com/AsharShakil/hr_dashboard.git'
devvalecha@Devs-Air hdashboard % git pull --rebase origin main
fatal: couldn't find remote ref main
devvalecha@Devs-Air hdashboard % git pull --rebase
There is no tracking information for the current branch.
Please specify which branch you want to rebase against.
See git-pull(1) for details.

    git pull <remote> <branch>

If you wish to set tracking information for this branch you can do so with:

    git branch --set-upstream-to=origin/<branch> master

devvalecha@Devs-Air hdashboard % git branch
* master
devvalecha@Devs-Air hdashboard % git push -u origin master
Username for 'https://github.com': iamasharshakil
Password for 'https://iamasharshakil@github.com': 
remote: Support for password authentication was removed on August 13, 2021.
remote: Please see https://docs.github.com/get-started/getting-started-with-git/about-remote-repositories#cloning-with-https-urls for information on currently recommended modes of authentication.
fatal: Authentication failed for 'https://github.com/AsharShakil/hr_dashboard.git/'
devvalecha@Devs-Air hdashboard % git push -u origin master
Username for 'https://github.com': iamasharshakil
Password for 'https://iamasharshakil@github.com': 
remote: Support for password authentication was removed on August 13, 2021.
remote: Please see https://docs.github.com/get-started/getting-started-with-git/about-remote-repositories#cloning-with-https-urls for information on currently recommended modes of authentication.
fatal: Authentication failed for 'https://github.com/AsharShakil/hr_dashboard.git/'
devvalecha@Devs-Air hdashboard % git push -u origin master
Username for 'https://github.com': iamasharshakil
Password for 'https://iamasharshakil@github.com': 
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Delta compression using up to 8 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 31.48 MiB | 2.12 MiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/AsharShakil/hr_dashboard.git
 * [new branch]      master -> master
branch 'master' set up to track 'origin/master'.
devvalecha@Devs-Air hdashboard % 
