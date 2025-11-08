# HW3A Solution — Git and Version Control

## Part 1: Repository Cloning
- I cloned the instructor repository into `class_repo`.
- I checked the remote and recent commits.

 ## Part 2: Portfolio Repository Creation
- I created `my_repo` with `homework/`, `projects/`, and `notes/`.
- I added `README.md` and `.gitignore`.
- I committed the changes.

## Part 3: GitHub Publishing
-

 I created a public GitHub repository named `py4eda-work`.
- I set the remote `origin` to: https://github.com/IsmailAuburn/py4eda-work
- I pushed the local `main` branch to GitHub.
## Questions

### Reflections
1. **How is using Git better than just saving “final_v2_reallyfinal.docx”?**  
   Git keeps a clean history of each change with a message, so I can go back to any version. It also separates “files I am editing” from “files I committed,” which is safer than manually copying files.

2. **Why do we have two repos (the instructor repo and my own repo)?**  
   The instructor repo is read-only so I can always pull class materials without breaking them. My own repo is where I keep my work and push it to GitHub to submit.

3. **Why are good commit messages useful?**  
   A message like “Add Part 3 GitHub publishing” tells me exactly what changed. Generic messages like “update” are not helpful when I look back later.


### Graduate Questions

#### Question 1: The Three-Stage Model
a) It was valuable to commit `README.md` and `.gitignore` first, and then `homework/hw3a-solution.md`, because those first two files belong to “setting up the repo.” Making that a separate commit keeps the history clean. If I had committed everything at once, I couldn’t easily see where the setup ended and the homework began.  
b) I would commit the finished or independent changes now (fix typo, update README, working code). I would wait to commit the half-finished analysis function. The staging area lets me add only the ready files to the next commit so I don’t mix complete and incomplete work.  
c) `git status` shows me what changed, what is staged, and what will be committed. I should run it before every commit so I don’t accidentally commit extra files.

#### Question 2: Local vs. Remote Repositories
a) Git is “distributed” because my local clone has the full repository history and I can commit even without GitHub. That’s different from Google Drive/Dropbox which only store files and don’t track commits.  
b) This is useful because I can work locally and commit many times, then later push to GitHub to share/backup. Developers aren’t blocked by the server.  
c) I can pull from `class_repo` but not push because it’s the instructor’s repository and I only have read access. My own `my_repo` is mine, so I can both push and pull.

#### Question 3: Professional Portfolio
a) I should commit work that shows progress and learning, but I should not upload private data, passwords, or other students’ solutions. Small, meaningful commits are better.  
b) A portfolio README should tell who I am, what this repo is for, and how it’s organized (`homework/`, `projects/`, `notes/`). That’s different from an open-source README, which is more about how to install/use the project.  
c) Building the portfolio during the course creates a real history. The habits I should keep: commit often with good messages, organize folders, and push to GitHub regularly so the repo is always current.

git add homework/hw3a-solution.md
git commit -m "Add graduate questions"
git push

git add homework/hw3a-solution.md
git commit -m "Add graduate questions"
git push
git add homework/hw3a-solution.md
git commit -m "Add graduate questions"
git push

### Graduate Questions

#### Question 1: The Three-Stage Model
a) It was valuable to commit `README.md` and `.gitignore` first, and then `homework/hw3a-solution.md`, because the first commit is “setup” and the second commit is “homework.” That keeps the history clear. If everything was in one commit, it would be harder to see what was repo setup versus assignment work.  
b) I would commit the finished or independent items now (fixing a typo, updating README, working code). I would wait to commit the half-finished analysis function. The staging area lets me add only the ready files so my commit doesn’t contain broken work.  
c) `git status` shows what changed and what is staged, so I should run it before every commit to make sure I am committing exactly the files I want.

#### Question 2: Local vs. Remote Repositories
a) Git is “distributed” because my local copy has the whole repo and I can commit even without GitHub. That’s different from cloud storage, which just syncs files but doesn’t give me commits, history, or branches.  
b) This is valuable because I can work locally, make several commits, and later push to GitHub to back up or share. It’s good for developers who are sometimes offline.  
c) I can pull from `class_repo` but not push because it’s the instructor’s repo and I don’t have write access. My own `my_repo` is mine, so I can both push and pull.

#### Question 3: Professional Portfolio
a) I should commit work that shows learning and progress, but avoid committing sensitive data or other students’ work. Small, logical commits are easier to review.  
b) A good portfolio README says who I am, what this repo is for, and how to navigate `homework/`, `projects/`, and `notes/`. That’s different from an open-source README, which is usually about how to install and use the project.  
c) Building the portfolio during the course gives me a real history to show later. The habits to keep are: commit often with clear messages, keep folders organized, and push to GitHub regularly so the repo stays current.
