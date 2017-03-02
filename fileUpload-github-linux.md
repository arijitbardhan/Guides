#
**Uploading a file to GitHub from a linux machine**
#
  1.  Create a new repository in GitHub. Or use any existing repository.
  2.  Clone the repository
  
    (a)	Click on **`Clone or Download`**. Copy the URL of the repository.
    
    (b)	On Terminal, change the directory to the place you want to clone your GitHub repository.
    
    (c) Execute **`git clone COPY_URL`**. Put the URL that you copied.
    
    (d) Your repository will be cloned to your local system.
    
  3.  Place the file that you want to upload in the cloned repository.
  
  4.  Stage the file for commit. **`git add FILE_NAME`**
  
  5.  Commit the file that you have staged.**`git commit -m "description"`**
  
  6.  Push the changes to GitHub. **`git push origin *your-branch*'**
