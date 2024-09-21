echo "# darryl-clay-7-27-24-multi-page-pyx5wjhanbhyyxe5net1qi0zhccnqxsqj6ug0hbex6" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/DarrylClay/darryl-clay-7-27-24-multi-page-pyx5wjhanbhyyxe5net1qi0zhccnqxsqj6ug0hbex6.git
curl -sS https://webi.sh/gh | sh
gh auth login
git config user.name "DarrylClay"
git config user.email "darryljclay14@gmail.com"
git commit -m "insert your memo here"
git add .
git push -u origin main