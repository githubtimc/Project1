From the website:
http://product.hubspot.com/blog/git-and-github-tutorial-for-beginners

Using the command line
Step 1: 
Create a local git repository 
EG H:\GitHub\Repositories\notes

Step 2:
To initialize a git repository in the root of the new folder, run the "git init" command:

Step 3: Add a file to the staging environment

Step 4: Create a commit
Run the command git commit -m "Your message about the commit"
The message at the end of the commit should be something related to what the commit contains - maybe it's a new feature, maybe it's a bug fix, maybe it's just fixing a typo. Don't put a message like "asdfadsf" or "foobar". That makes the other people who see your commit sad. Very, very, sad.

Step 5: Create a new branch
Branches allow you to move back and forth between 'states' of a project. For instance, if you want to add a new page to your website you can create a new branch just for that page without affecting the main part of the project. Once you're done with the page, you can merge your changes from your branch into the master branch. When you create a new branch, Git keeps track of which commit your branch 'branched' off of, so it knows the history behind all the files. 