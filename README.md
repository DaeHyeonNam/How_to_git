//Most basic functions

git init                                     //make this folder a git folder
	la -al                               // you may be able to find .git file.
vi README.md                                 //make a test file
git add README.md                            //make README.md file to be prepared to commit
	git status                           // you can check the status of each files
git commit -m "message"                      //commit the README.md file with the " "message 
	git log                	             // you can check the past commisions.
git remote add origin http://github.com/...  //connect the github page that you want to push
git push -u origin master                    //push to sync this folder with github folder


//roll back roll forward
git commit -a -m "" //Automatically add previously added files.
git log
git checkout 8e05   // Roll back and Roll forward. 


//git branch
git checkout -b branch1 //create new branch
git branch              //brach check
git checkout master     //move between branches
git merge branch1       // merge


