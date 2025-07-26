# # Navigate to your website folder
cd path/to/your/website-folder

# Initialize Git
git init

# Connect to your GitHub repo (replace URL)
git remote add origin https://github.com/yourusername/your-repo-name.git

# Add files to staging
git add .

# Commit changes
git commit -m "First website upload"

# Push to GitHub (use main or master branch)
git branch -M main   # Switch branch name if needed
git push -u origin main
