# 1️⃣ Create a new repository on GitHub
# Go to github.com → New Repository → Create

# 2️⃣ Copy HTTPS repository link
# GitHub → Code → HTTPS → Copy link

# 3️⃣ Clone the repository to local machine
git clone https://github.com/USERNAME/REPOSITORY.git

# 4️⃣ Go inside the project folder
cd REPOSITORY

# 5️⃣ Check current status
git status

# 6️⃣ Make changes / modify files
# (Edit files using VS Code or create new files)

# Create a new file
touch file.txt

# 7️⃣ Check status after changes
git status

# M = Modified
# U = Untracked

# 8️⃣ Stage files (add to staging area)

# Add a single file
git add file.txt

# Add all files
git add .

# 9️⃣ Commit staged changes
git commit -m "Your commit message"

# 🔟 Push changes to GitHub

# First time push
git push -u origin main

# Next time push
git push
