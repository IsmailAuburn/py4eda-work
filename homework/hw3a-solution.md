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
**a)** Committing `README.md` and `.gitignore` first made sense because those two files are part of “setting up the repo.” Putting them in their own commit keeps the history clean. Then the commit with `homework/hw3a-solution.md` clearly shows “this is the actual assignment.” If I had committed everything at once, I wouldn’t be able to tell where setup ended and homework started.

**b)** From that list I would commit the finished things now (code to load data, typo fix, README update) and wait on the half-finished analysis function. The staging area helps because I can add only the complete pieces to the commit and leave the unfinished code unstaged until it’s ready.

**c)** `git status` tells me what changed and what is staged, so I know exactly what will go into the next commit. I should run it a lot — especially right before `git commit` — so I don’t commit files by accident.

#### Question 2: Local vs. Remote Repositories
**a)** Git is “distributed” because my local clone has the entire repo and history, so I can work and commit without being connected. That’s different from Google Drive/Dropbox, which mainly just sync files and don’t track commits.

**b)** This is useful because I can do real work offline (edit, commit, look at history) and then later `git push` to GitHub when I’m online. It lets developers work independently and sync when they’re ready.

**c)** `git clone` is the first download. `git pull` gets new changes from the remote. `git push` sends my commits up. I can pull from `class_repo` but not push because I don’t have write access. I can push to `my_repo` because I own that remote.

#### Question 3: Professional Portfolio
**a)** I should commit things that actually show progress (finished homework, cleaned notebooks) and avoid committing sensitive stuff or other people’s work. It’s okay to show the process, but the main branch should stay in a good state.

**b)** A portfolio README should introduce me, say which class this is for, and show where to find homework/projects. An open-source README is more about how to install and use the code.

**c)** Doing this during the semester builds a real timeline instead of dumping everything at the end. Good habits: commit often with clear messages, keep the repo organized, and push to GitHub regularly.
