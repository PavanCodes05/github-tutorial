Installing Git
You can install Git on any operating system using these methods :​

Windows
Visit git-scm.com and download the latest installer.

Run the installer and keep the default settings.

Open Git Bash from the Start menu after installation.

Verify installation:

bash
git --version
macOS
Using Homebrew:

bash
brew install git
Or download and install the .dmg package from git-scm.com.

Verify installation:

bash
git --version
Linux (Ubuntu/Debian)
Update your package list and install Git:

bash
sudo apt update
sudo apt install git -y
Verify your installation:

bash
git --version
Configure your Git credentials:

bash
git config --global user.name "Your Name"
git config --global user.email "your_email@example.com"

Common Git Commands:
Command                 	Description
git init    	            Initialize a new repository in the current folder
git clone <repo_url>	    Clone an existing repository
git status	                Check the current status of files
git add <file>	            Add file(s) to the staging area
git commit -m "message"  	Record changes with a commit message
git branch	                List all branches
git branch <name>	        Create a new branch
git checkout <branch>    	Switch to another branch
git merge <branch>	        Merge another branch into the current one
git pull	                Fetch and merge changes from the remote repository
git push	                Upload local commits to the remote repository
git log	                    View commit history
git diff	                Show file differences before committing
git config --global user.name "Your Name"   	Set username globally
git config --global user.email "Your Email"	     Set email globally
