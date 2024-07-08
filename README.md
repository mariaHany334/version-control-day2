< Question 4>

# Remove local branches
git branch -d dev
git branch -d test

# If branches are not fully merged, force delete
git branch -D dev
git branch -D test

# Remove remote branches
git push origin --delete dev
git push origin --delete test

<question 5>

# Stash your changes
git stash

# Checkout another branch
git checkout branch-name

# (Optional) Apply and remove stashed changes
git stash pop

