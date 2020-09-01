Now that you have "Commited" the file, that means is permanently stored in Git.

### To test it out

Now delete the "hello.txt" file. 
Right click on the file > Delete

Check what is the status of the repository:

`git status`{{execute}}

Now reset the repository to the last commit:
`git reset --hard`{{execute}}

You have now recovered the file.