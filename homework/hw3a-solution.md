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

#### Question 1: Git workflow benefits
**a.** Before this assignment I usually kept different versions by saving new files (like “report-final.docx”, “report-final2.docx”). That works for small things, but it’s easy to lose track and it doesn’t tell you what actually changed. Git is better because:
1. it keeps one copy with full history,
2. every change has a message,
3. you can go back to any earlier version.

**b.** A place where Git history would have helped is working on a group assignment where we kept editing the same file. If we had commits, we could see who changed what and roll back if someone broke the file.

#### Question 2: Repository organization
**a.** We keep the instructor repo and our own repo separate so we don’t mess up the class materials. The class repo is read-only; our repo is where we do the work and push to GitHub. If everything was in one repo, we could accidentally edit or commit things that belong to the instructor.

**b.** In future projects I would do the same: one “source” repo for starter files or shared data, and one working repo for my changes. That makes it easier to pull updates without mixing them with my homework.

#### Question 3: Commit messages and history
**a.** “Add hw3a solution documenting Git workflow and repository structure” is better than “update” because it tells me exactly what changed. Later, if I search the log, I can find that commit. “update” is useless.

**b.** Good commit messages are useful over time because they tell the story of the project. If something breaks, I can look back and see which change caused it.
.


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
