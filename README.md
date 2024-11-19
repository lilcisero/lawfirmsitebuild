# lawfirmsitebuild
Building a template law firm website 

To Do 

Figure out how to use github to upload files for github pages site 

Navigate to Your Project Directory: Open your terminal and navigate to your project directory:

sh
cd ~/Desktop/github_desktop_buildtwo
Initialize a Git Repository (if not done already): If you haven’t initialized a Git repository in this directory, do so now:

sh
git init
Add Your Project Files to the Repository: Add all your files to the staging area:

sh
git add .
Commit Your Files: Commit your files with a relevant message:

sh
git commit -m "Initial commit with project files"
Add the Remote Repository: Assuming you have already created a repository on GitHub, add the remote URL:

sh
git remote add origin https://github.com/yourusername/yourrepo.git
Push Your Changes to GitHub: Push your committed changes to the remote repository:

# so for you it is 
# https://github.com/lilcisero/lawfirmsitebuild
# git remote add origin https://github.com/lilcisero/lawfirmsitebuild

sh
git push -u origin master
Enable GitHub Pages:

Go to your repository on GitHub.

Click on the "Settings" tab.

Scroll down to the "GitHub Pages" section.

Under "Source," select the branch you want to publish (e.g., master or main).

Click "Save."

Your website should be live at https://yourusername.github.io/yourrepo.