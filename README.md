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
- **Branch**: A separate version of your main repository that lives in the same area. You can make changes to the branch without tampering your main repository, and merge the two if you are content with the results. 

- **Clone**: An offline copy of your main repository that's stored on your system's harddrive instead of a website's server. Having a copy of the repository allows you to use an IDE or development tools that you want, while still be able to push this version back to your GitHub.



- **Commit**: A change to a file on your repository that's recorded and can be viewed publicly or privately. Can be seen as a sort of change-log.


- **Fetch**: To add changes from one repository to another without fully changing them. Before you do commit, fetching allows you to check the changes first.


- **GIT**: An open source program that allows to track changes made to a program that you're working on. Necessary to have if you want to connect Webstorm or other IDE's directly to GitHub to push your project from the workstation of your choice.

- **Github**: A hub and service where you can upload your various coding projects as files known as repositories. This service is open for singular users or entire organizations.


- **Merge**: To take one form of a branch and merges it with another one, as long as they are all in the same repository.
 

- **Merge Conflict**: When an error happens on one of the merged branches. An error could include a line of code not functioning properly which causes the entire branch to fail, or if one of the merged branches are deleted. 


- **Push**: To send your offline/local work to the online repository for either public or private access on the Git server. The server does not check before you push items. 


- **Pull**: To download a revised revision of a branch from the server to merge it with your local copy on your system. Comes incredibly handy when developing as a team. 


- **Remote**: This is the version of a repository or branch that is hosted on a server, most likely GitHub.com. Remote versions can be connected to local clones so that changes can be synced.
A version of the repository or branch that is hosted on the GitHub server (or any other server). Can either be edited from the server remotely, or downloaded to your system and edited locally. 

- **Repository**: Basic file storage of all your branches, files, and other documentation related to your project. Repositories are located on the GitHub server and can be accessed by all people publicly or be kept as a private project. 

## Resources Used:
- https://docs.github.com/en/github/getting-started-with-github/github-glossary#clone
- Create Github Account PowerPoint
