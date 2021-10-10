# git-bitbuket-sourcetree

# Git
- Distributed Version Control System

# Resources
- http://web.archive.org/web/20090210020404id_/http://whygitisbetterthanx.com/#the-staging-area
- https://stackoverflow.com/questions/292357/what-is-the-difference-between-git-pull-and-git-fetch?rq=1
- https://git-scm.com/book/en/v2
- https://stackoverflow.com/questions/3689838/whats-the-difference-between-head-working-tree-and-index-in-git
- https://hackernoon.com/understanding-git-index-4821a0765cf![image](https://user-images.githubusercontent.com/42272776/136692077-3613c73f-f539-402e-b913-ad8e57c76159.png)

# Questions
- Why is Git DVCS
  - If the central server goes down, would you still be able to clone?
- What is ORIGIN
- Understand Git CHECKOUT
- Hands on on Git MERGE vs FETCH & MERGE
- What is HEAD?.
- Resolve MERGE CONFLICT via command line
- What is REBASE?.

# Terminology
| Name      | Meaning |
| ----------- | ----------- |
| Working Directory | This is where you are currently working on |
| Staging Area | Also called as Index. Helps in cases where you want to make many changes but proceed with few. This is in the .git/index folder in the working directory |
| Local Repo | Local repository. This is in the .git folder. This is in .git folder as well |
| Remote Repo | The repository that is hosted on your organization/cloud |
| Git PULL | Combination of FETCH and MERGE. Touches both Local Repo and Index |
| Git FETCH | Touches Local Repo |
| Git MERGE | Touches Working Directory |
| Git CHECKOUT | Used for switching between branches |
| Git PUSH | User for pushing content from local repo to remote repo |

- ![image](https://user-images.githubusercontent.com/42272776/136691627-e0872ccd-1429-412e-8bc1-a3978389c490.png)
- ![image](https://user-images.githubusercontent.com/42272776/136691950-e0650b49-abd8-4378-8fb7-1477313854c8.png)

# Commands

| Name      | Meaning |
| ----------- | ----------- |
| git status | List those files which differ between index and working directory |
| git ls-files | List all those files in the Index |
| git add <filename> | Adds a file to the Index |
| git commit -m "commit message" | Commit the file to the local repository |
| git commit -am "commit message" | Adds a file to the Index and commits the file to the local repo |
  
  
