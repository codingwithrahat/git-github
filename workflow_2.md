# 1️⃣ Create a local project folder
mkdir my_project

# 2️⃣ Go inside the folder
cd my_project

# 3️⃣ Create files (example)
touch README.md
touch main.cpp

# 4️⃣ Initialize git repository
git init

# 5️⃣ Check git status
git status

# 6️⃣ Add files to staging area

# Add a single file
git add README.md

# Add all files
git add .

# 7️⃣ Commit the files
git commit -m "Initial commit"

# 8️⃣ Create a new repository on GitHub
# (Do NOT initialize with README)

# 9️⃣ Copy HTTPS repository link from GitHub

# 🔟 Add remote repository
git remote add origin https://github.com/USERNAME/REPOSITORY.git

# Check remote
git remote -v

# 1️⃣1️⃣ Set branch name to main
git branch -M main

# 1️⃣2️⃣ Push local repo to GitHub (first time)
git push -u origin main

# 1️⃣3️⃣ Next time workflow
# Modify files → git add → git commit → git push
