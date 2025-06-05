# **REFLECTION OF SBA**
### Steps to create and manage branches.
* ##### Steps I took to create and manage branches would first be to initialize my branch and rename it "main" using git branch -m 
* ####  I then added my index.html, staged, and committed. Then finished it off with (code .) to bring it into VSCODE.
* #### After opening VSCODE, I then created a branch to feature the header and footer. (git checkout -b feature/header, git checkout -b feature/footer)
* #### Once those were opened, I saved my files after each command for each branch and after each change, then staged and committed. (git add index.html, git commit -m "...")
  
### How was the merge conflict handled?
#### The merge conflict was handled by being prompted with an error code for merging when a branch index was used within another branch index while editing the HTML script. Once VSCODE detected the error, it gave a side-by-side comparison of where the error was coming from and a comparison of the two branches it was detected. I went in to fix the necessary code in the script and got rid of the additional footer and keeping the footer I wanted. I then saved files, staged, and committed the merge error. (git add . , git commit -m "resolved merger conflict"). It also froze the keyboard, given me a layout of what should be fixed where I then used  ( esc : wq) to access keep and then committed (git commit -m "merger completed")

### How the pull request process helped you ensure code quality and collaboration.
#### Using the pull request ensured the changes in the script and its testing, it also documented within GitHub, which means that the merge has to be successful before a pull request is pushed through with the git command (git push origin or file name). Others can see or make a change in the code with the collaborators for feedback, review, or compliments.
