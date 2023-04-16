# Initiate Git repository locally
1) open a project
2) create an empty folder to hold future repository
3) add a Read Me file to empty folder
4) use command line git init to initialize folder as repository
5) use command line git add to track Read Me file 
6) use command line git commit to save Read Me file locally
# Make local Git repository live on GitHub
1) with locally created git repository a remote connection to GitHub is not established
2) create a new empty repository on GitHub to create a repo to clone for connecting locally
3) use command line git remote add origin (paste cloned GitHub repo) to add a reference to the remote repo on GitHub
4) use command line git remote -v to show all remote repositories connected to this local git repo
5) now a remote connection has been established between GitHub and the local machine
6) now the local repo may be pushed remotely
5) use command line git push orgin mainstem to push the repo created locally to GitHub
