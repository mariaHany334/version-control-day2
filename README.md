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
