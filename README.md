Quick setup — if you’ve done this kind of thing before
 Set up in Desktop	or	
 HTTPS
 SSH

https://github.com/yatincit/testapp.git

We recommend every repository include a README, LICENSE, and .gitignore.
…or create a new repository on the command line

echo "# yatindemo" >> README.md
git init
git add README.md
git commit -m "first commit"
git remote add origin https://github.com/yatincit/testapp.git
git push -u origin master

…or push an existing repository from the command line

git remote add origin https://github.com/yatincit/testapp.git
git push -u origin master


…or import code from another repository
You can initialize this repository with code from a Subversion, Mercurial, or TFS project.
