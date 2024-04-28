# Git Assignment - duggsun
a.	What is an issue?
An issue is an item we can create in a repository to plan, discuss and track work. They are simple to create and can be used to track work, give, or receive feedback, collaborate on ideas or tasks, and efficiently communicate with others.

b.	What is a pull request?
Pull request is a way to tell others about changes we've pushed to a branch in a repository on GitHub. Using a pull request, we can discuss and review the potential changes with collaborators and add follow-up commits before the changes are merged into the base branch.

c.	How do I open up a pull request?
On GitHub, navigate to the main page of the intended repository. In the "Branch" menu, choose the branch that contains the commits. Above the list of files, click Compare & pull request to create a pull request for the associated branch. And finally, click New pull request to open up a pull request.

d.	Give me a step by step guide on how to add someone to your repository.
Step 1 - Under your repository name, click Settings. 
Step 2 - In the "Access" section of the sidebar, click Collaborators. 
Step 3 - Click Add people. Enter username or email. Send invite.

e.	What is the difference between git and GitHub?
Git is a version control system which allows us to have different versions of programs stored and be able to do various things such as compare previous code with new code or be able to merge with somebody else’s code. Whereas GitHub is a cloud-based service to host the repositories or folders of projects. 

f.	What does git diff do?
git diff compares what is in our working directory to what is in our staging area. If we've made changes to our files without running git add, we'll see the comparison. If there are no differences, nothing will be shown.

g.	What is the main branch?
main is the default branch that GitHub displays when anyone visits our repository. The default branch is also the initial branch that Git checks out locally when someone clones the repository. Unless specified otherwise, the default branch in a repository is the base branch for new pull requests and code commits.

h.	Besides our initial commit if it is a new repository, should we directly push our changes directly into the main branch?
No, we should create separate branches for each feature, bug fix, or release, and merge them into the main branch once we're confident that our changes are stable and tested. Working directly in the main branch can make it hard to review changes and track issues in our codebase.
