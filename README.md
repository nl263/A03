# A03
## How to set up Webstorm for GitHub usage:
- Go to the JetBrains website and sign up for an education license using your University email:
- https://www.jetbrains.com/student/
- Once your account and license has been secured, you should be redirected to a downloads page.
- Find the Webstorm download, click on it, download the version that works with your operating system, and install it.
- Webstorm will be your IDE specifically made for HTML development
- After installing Webstorm, open up the .exe file and log into your JetBrains account. 
- Once logged in, a window with multiple options, similar to Android studio, will pop up.
- In the top left hand corner, click on the file tab, choose HTML, HTML5 and Webstorm will generate a new HTML file where you can start coding away.
- Now, in order to let Webstorm interact with GitHub and allow you to directly send your projects to a repository that you created
- Download git from www.git-scm.com/downloads and install it as a Local Program.
- Go to the GitHub website and create a GitHub account.
- To Connect GitHub with Webstorm, on the Webstorm window press Ctrl+Alt+S together.
- This will bring up the System Preferences window.
- Where it says "Path to Git executable" select where you installed the Git download. 
- Now it's time to create a repository and send your first file from Webstorm to GitHub
- Go to your GitHub page:
- Click on the plus sign in the upper right hand corner of the page and choose "Create New Repository"\
- Make the repository public and make sure to add the README.Md File
- In Webstorm, select VCS and Import into version control.
- Enter the GitHub repository URL and the Local path of the HTML project on your pc
- Open up the Add to Git window, and select all of your HTML files.
- Once done, press the commit option.
- Press down on Ctrl+Shift+K and press the Push button.
- This will send your files that you committed to your GitHub repository that you linked to Webstorm. 
- Congratulations, your file is now on GitHub.

## Glossary of Important Words to Know Before Using GitHub
- **Branch**: A branch is a parallel version of a repository. It is contained within the repository, but does not affect the primary or main branch allowing you to work freely without disrupting the "live" version. When you've made the changes you want to make, you can merge your branch back into the main branch to publish your changes.
- **Clone**:A clone is a copy of a repository that lives on your computer instead of on a website's server somewhere, or the act of making that copy. When you make a clone, you can edit the files in your preferred editor and use Git to keep track of your changes without having to be online. The repository you cloned is still connected to the remote version so that you can push your local changes to the remote to keep them synced when you're online.


- **Commit**:A commit, or "revision", is an individual change to a file (or set of files). When you make a commit to save your work, Git creates a unique ID (a.k.a. the "SHA" or "hash") that allows you to keep record of the specific changes committed along with who made them and when. Commits usually contain a commit message which is a brief description of what changes were made.


- **Fetch**: When you use git fetch, you're adding changes from the remote repository to your local working branch without committing them. Unlike git pull, fetching allows you to review changes before committing them to your local branch.


- **GIT**:Git is an open source program for tracking changes in text files. It was written by the author of the Linux operating system, and is the core technology that GitHub, the social and user interface, is built on top of.


- **Github**:GitHub provide a service to an entire organization and use their own identity when performing their function. They can be installed directly on organizations and user accounts and granted access to specific repositories. They come with granular permissions and built-in webhooks.


- **Merge**: Merging takes the changes from one branch (in the same repository or from a fork), and applies them into another. This often happens as a "pull request" (which can be thought of as a request to merge), or via the command line. A merge can be done through a pull request via the GitHub.com web interface if there are no conflicting changes, or can always be done via the command line.


- **Merge Conflict**: A difference that occurs between merged branches. Merge conflicts happen when people make different changes to the same line of the same file, or when one person edits a file and another person deletes the same file. The merge conflict must be resolved before you can merge the branches.


- **Push**: To push means to send your committed changes to a remote repository on GitHub.com. For instance, if you change something locally, you can push those changes so that others may access them.


- **Pull**: Pull refers to when you are fetching in changes and merging them. For instance, if someone has edited the remote file you're both working on, you'll want to pull in those changes to your local copy so that it's up to date. See also fetch.


- **Remote**: This is the version of a repository or branch that is hosted on a server, most likely GitHub.com. Remote versions can be connected to local clones so that changes can be synced.


- **Repository**: A repository is the most basic element of GitHub. They're easiest to imagine as a project's folder. A repository contains all of the project files (including documentation), and stores each file's revision history. Repositories can have multiple collaborators and can be either public or private.


