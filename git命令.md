…or create a new repository on the command line

echo "# website" >> README.md
git init
git add README.md
git commit -m "first commit"
git remote add origin https://github.com/hare1925/website.git
git push -u origin master

…or push an existing repository from the command line

git remote add origin https://github.com/hare1925/website.git
git push -u origin master

…or import code from another repository

You can initialize this repository with code from a Subversion, Mercurial, or TFS project.
