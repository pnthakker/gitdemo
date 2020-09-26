# Demo

This is for Git Demo

Steps followed to create this git repo using CLI:

touch README.md
git init
git add README.md
git commit -m "first commit"
git remote add origin git@github.com:pnthakker/gitdemo.git
curl -u 'parth8@yahoo.com' https://api.github.com/user/repos -d '{"name":"gitdemo"}'
git push -u origin master

Also created gitdemokey (ssh) and associated it with github