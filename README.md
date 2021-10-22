1.	“I CAN WIN” Task
1.1	Install git and generate a pair ssh keys. Authorize public key in github.com.
1.2	Set your user.name and user.email in git.
1.3	Create a new repository in github.com and clone it locally to your machine.
1.4	Create a file with name “song.txt” and put a half of the text of your favorite song to it.
1.5	Make commit with name "add first half of my favorite song" and send it to the server.
1.6	Make sure there is the file “song.txt” in github now and it contains a half of the song text.
1.7	Using github web-interface add the second half of song text and make commit with name "finish my song".
1.8	In your local repository pull the changes and make sure that the changes made with the second commit are available, and you are able to see full text of the song. 

2.	“I BRING IT ON” Task
This task is based on the previous one (“I Can Win”)
2.1	Add to your project file .gitignore and set this up to hide files with extensions .db, .log, etc. and folders with names ‘target’ , ‘bin’ etc.
2.2	Create a branch ‘feature’ and make two commits to it.
2.3	Merge ‘feature’ branch to ‘master’.
2.4	Navigate back to ‘feature’ branch and create a file ‘arrows.txt’ with the content as below:
The ship glides gently on the waves
As day turns into night
Make commit.

2.5	Switch to ‘master’ branch. Create there a file ‘arrows.txt’ with content as below:
One thousand burning arrows
Fill the starlit sky
Make commit.

2.6	Merge ‘feature’ to ‘master’ resolving conflict: save all 4 strings in file ‘arrows.txt’ in the same order  how they were added in steps 2.4 and 2.5.



3.	“HURT ME PLENTY” Task
This task is based on the previous one (“Bring It On”).
3.1	Create a branch ‘storm’ and add commit to file ‘storm.txt’:
Twenty ships with Norsemen braves
Riding the northern wind
3.2	Add 2 more strings in ‘storm.txt’ and make one more commit:
They left their shores at early dawn
As a red sun was rising in the east
3.3	Switch to ‘master’ and create a file ‘pursuit.txt’ with content as below:
The warming sun returns again
And melts away the snow
The sea is freed from icy chains
Winter is letting go
Make commit.
3.4	Mark the commit with tag ‘session1’ and switch to branch ‘storm’
3.5	Make rebase of ‘storm’ branch in the way it contains the last commit from ‘master’ branch.

4.	“HARDCORE” Task:
This task is based on the previous one (“Hurt Me Plenty”).
4.1	Push your repository and make sure all commits appeared in github.
4.2	Create a new repository in github.
4.3	Set up remote in local repository in the way that allows:
- pull from the first (initial) remote repository, 
- push to the second (new) remote repository.
4.4	Make push and make sure the second repository in github is identical to the first one.
4.5	Get initial settings back for remote: pull and push of local repository hit the same remote repository in github.
