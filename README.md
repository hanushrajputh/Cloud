# Just a dummy repo to host images and some commands 

# Git Commands Cheat Sheet

## 🔁 Initial Setup (New Project or Replacing Old Code)
```bash
git init                                       # Initialize a new Git repo  
git remote add origin <repo-url>              # Link to your GitHub repo  
git add .                                      # Stage all files  
git commit -m "Initial commit"                # Commit your changes  
git branch -m main                            # Rename branch to 'main'  
git push origin main --force                  # Push and overwrite remote main branch  
````

## 🔄 Everyday Workflow (For Ongoing Work)

```bash
git status                                     # Check current changes  
git add .                                      # Stage all changes  
git commit -m "Your message here"             # Commit changes  
git push origin main                           # Push to GitHub  
```

## ⬇️ If You Need to Pull Remote Changes

```bash
git pull origin main                           # Pull updates from GitHub  
```

## 🌿 Working with Branches

```bash
git checkout -b new-feature                    # Create & switch to new branch  
git switch main                                # Go back to main branch  
git push origin new-feature                    # Push new branch to GitHub  
```

## 🧹 Reset & Clean (Danger Zone 🚨)

```bash
rm -rf .git                                    # Remove Git history (start over)  
git init                                       # Re-initialize Git repo  
```

## 🔧 Other Handy Commands

```bash
git log                                        # Show commit history  
git remote -v                                  # Check current GitHub remote  
git branch                                     # Show current branches  
git branch -m new-name                         # Rename current branch  
mm
```


