Git test File
Git is Free software

Git init                    //init git
Git status		    //file status
Git add <fileName>	    // add file stage 
Git commint -m 'commit mesage'	//commit stage file to master
Git reset --hard HEAD^	    // callback last version
Git reset --hard <commit_id>	//callback commit_id version
Git reset HEAD <fileName>		//delete stage file
Git log				// git commit log
Git reflog --pretty=oneline	//command log 
Git diff <fileName>		//comparison master difference
Git rm <fileName>			//delete filaName for master
Git checkout --<fileName>		//checkout new version for  master

///////////////////////////////////////////////////////////////
Git remote add origin git@github.com:kevinlew/learngit.git  //cheout
Git push -u origin master	//Branch master set up to track remote branch master from origin.
Git push origin master		//submit to master
Git clone git@github.com:michaelliao/learngit.git
Git checkout -b dev              
Git branch
Git checkout <master>         //switched to branch 'master'
Git merge  --no-ff -m 'merge version' dev	    //
Git log --graph --pretty=oneling --abbrev-commit
Git stash      //Saveed working directory and index state 
Git stash pop	// Saveed working callback
Git stash list
Git stash apply
Git stash drop
Git stash apply stash@{0}
Git branch -d dev
Git branch -D dev
Git remote 
Git remote -v
Git push origin master
Git push origin dev
Git checkout -b dev origin/dev
Git pull
Git branch --set-upstream dev origin/dev
Git tag v10.0
Git tag
Git tag <v1.>0 <commit_id>
Git show <v0.9>
Git tag -d <tagName>
Git push origin --tags
Git push origin:refs/tags/<tagName>
.gitignore     //git ignore file a file a line and must commit 
Git config --global alias.<alisaName> <command>
LG:
	git config --global alias.lg "log --color --graph --pretty=format:'%Cred%h%Creset -%C(yellow)%d%Creset %s %Cgreen(%cr) %C(bold blue)<%an>%Creset' --abbrev-commit"   
     git lg == git log --color --graph......

git config --global alias.st status     
	git st ==   git status

