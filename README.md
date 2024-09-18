# Raycast Goodies
Raycast snippets + goodies by @dfosco

### Simple Commands

#### Random Usernames

Add a random username to your clipboard from a list of 100 names. 

> [!TIP]  
> This list was created randomly with an LLM to be a somewhat accurate representation of GitHub usernames — might accidentally contain real people names, **don't use for designs that show up in production**!

![Raycast screenshot of random username command](images/image-2.png)

![Random username paulomoreira added](images/image-1.png)

#### Count Characters

For when you need to know if a text fits in your design... if you know you know.

![Raycast screenshot of Count Characters command](images/image-5.png)

![Output of character counts: The number of characters is 43](images/image-6.png)

---

#### Advanced Commands

> [!WARNING]  
> Before you can use these two commands, replace the contents of `_repositories-folder.txt` with the path of the folder where you keep repositories in your Mac

<detail>
<summary>Instructions to get repository folder path</summary>

![Instruction to Get info on folder](images/image-3.png)

![Instruction to get folder path](images/image-4.png)

The output copied to your clipboard will not include the actual folder name, so make sure to add it. 

In this case, the output was `/Users/dfosco` and I added `/Workspace` so the file contains a single line with:

```
/Users/dfosco/Workspace
```
</detail>

### Open Repo in VS Code

Quickly open any local repository in VS Code, just type its folder name.

![Raycast screenshot of Open Repo command](images/image.png)

> [!TIP]  
> You should have the VS `code` CLI command installed for this. To do so: 
> 1. Open VS Code
> 2. Press `cmd + shift + p`
> 3. Search for “code command” and choose the option below:
> ![VSCode option to install 'code' command in PATH](images/image-10.png)

### Commit Now

Quickly commit and push all files in a repository with commit message "Update `repo` @ `date - time`"

![Raycast screenshot of Commit now command](images/image-7.png)

![Screenshot of git commit messages generated by this command](images/image-9.png)