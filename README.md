# example
Example repository to demonstrate Github and recommended structure.

Please look at the Wiki pages for more information on setting up Github, and on using Github with RStudio.

Before setting up a new repository, please read this page on the recommended structure for a Github project within VUW Clustering, which explains how to set up the project in that way and why it's a good idea. (https://github.com/vuw-clustering/example/wiki/VUW-Clustering-Github-Repository-Structure)

## Cloning this repository onto your computer

If you're using RStudio, it's fairly simple to clone this repository into a new RStudio Project on your machine.

1. Go to the main code page for this repository. 

2. Click on the "Clone/Download" button, select the repository address (switch to HTTPS or SSH depending on what you're using to connect your local computer to Github).

3. Open RStudio, and select "New Project" from the file menu, then click on the third option, "Version Control".

4. Paste the repository url into the address box, and if you want, change which local folder the repository will be created in.

This will automatically clone a copy of the repository onto your computer, and link it to a new, local RStudio Project. Go to Tools --> Version Control --> History to see that you have a local copy of the entire repository history. 

The branch name that is showing at the top of that window should be "master", because by default the local repository will be on the master branch. Now you need to switch to the "development" branch because you do not have access rights to commit directly to the "master" branch for this example repository. For more details, see the wiki page on project structure: (https://github.com/vuw-clustering/example/wiki/VUW-Clustering-Github-Repository-Structure).

Switching to the development branch:

5. If you're not in the Version Control window within the RStudio project, open it via Tools --> Version Control --> Commit, or History. 

6. Click on the "Changes" button in the top left of the Version Control window.

7. Click on the word "master" at the top of the window, which should open a drop-down menu. This menu has sections which are indicated by the grey headers, and the grey headers correspond to the branches listed *below* them, even though the horizontal lines make it look like the grey headers are in separate sections from the text below.
At the bottom of this menu you will see a grey header that says "(REMOTE:ORIGIN)" and then a list of two branches, "master" and "development". These are the two branches that exist on the Github version of this repository, which is the "origin" copy of the repository. Above that, in the middle of that small drop-down menu, should be a grey header that says "(LOCAL BRANCHES)" which is the list of your local branches. 
If you do not see the same set of branches under "(LOCAL BRANCHES)" as you see under "(REMOTE:ORIGIN)", e.g. the Local Branches section only shows the "master" branch, then fetch a local copy of the "development" branch as well by clicking on the "development" link under the "(REMOTE:ORIGIN)" section. This will not only make a local copy of that remote development branch, it will also move the HEAD of your local repository onto that local development branch.
If you already have the same set of local branches as there are on the REMOTE:ORIGIN, then switch to the local development branch by clicking on "development" in the "(LOCAL BRANCHES)" section of the branch menu.
