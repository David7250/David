echo "# TEST1" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin git@github.com:David7250/TEST1.git
git push -u origin main
