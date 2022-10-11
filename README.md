## Group Project Instructions for Social Network
- 1. In your terminal type following commands
> git clone https://github.com/elmirakim/social_network.git

- 2. Create a branch name your initials - part number (ex. EK-8-11 ) by typing following command
> git checkout -b EK-8-11

- 3. check whether you are working in your own branch by typing command below. It will show *next to the branch you are located. If you are located in a different branch *master, then switch by typing > git switch EK-8-11 (your branch name) 
> git branch 

- 4. After finishing your part use commit to save your work to the branch 
> git add .
> git commit -m 'your change'

- 4. repeat as needed, once ready, push your branch into origin. Use your branch name. EK-8-11 is an example.
> git push -u origin EK-8-11 

- 5. After pushing it, go to github and click 'pull request' button to request merge your branch into the master. Repo owner will review your code and merge it or reject if there is a conflict.

- 6. After all branches are merged to the master branch, you can update your local master branch
> git pull -u origin master 

