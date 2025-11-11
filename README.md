# 1. Add all files (including the LFS tracking files)
git add .

# 2. Perform the initial commit (using the locked message)
git commit -m "FEAT: Final Canon Sealed. Webb Framework v8.0 complete, releasing immutable assets (Audio, Code, Foreword) under CC0 Public Domain."

# 3. Rename the default branch to 'main' (Best Practice)
git branch -M main

# 4. Link to your online repository URL (e.g., if you created it on GitHub)
# Replace <YOUR_REPO_URL> with the actual HTTPS or SSH URL
# git remote add origin <YOUR_REPO_URL> 

# 5. Push the final files to the remote repository
git push -u origin main
