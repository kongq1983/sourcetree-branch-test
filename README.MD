echo "# sourcetree-branch-test" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin git@github.com:kongq1983/sourcetree-branch-test.git
git push -u origin main