 github

 <h6> to create a directory and navigate to it </h6>

mkdir first_git_repo
cd first_git_repo

 Initialize a Git repository

git init

to create one.py file with content

echo "print('one')" > one.py
echo "x = [1, 2, 3]" >> one.py
echo "y = [4, 5, 6]" >> one.py

 Commit one.py

git add .
git commit -m "python program"

to create two.py file with content

echo "print('two')" > two.py

 Check the status

git status

 to create a new branch update-2

git branch update-2

 Switch to update-2 branch

git checkout update-2

 Commit two.py in update-2

git add two.py
git commit -m "Add two.py in update-2"

 Switch back to master

git checkout master

 Merge update-2 into master

git merge update-2

 to create a branch named update-3

git branch update-3

 to create three.py file with content

echo "print('three')" > three.py

 to create README.md

echo " Hello, venkat" > README.md
echo "To run \`update-3\`, execute \`python3 three.py\`" >> README.md

 Commit three.py and README.md

git add three.py README.md
git commit -m "Add update-3 and README.md"

 Switch to master branch

git checkout master

 to create a new branch named update-4

git branch update-4

 to create four.py file with content

echo "print('four')" > four.py

 to create README.md for update-4

echo " Hello, venkat" > README.md
echo "To run \`update-4\`, execute \`python3 four.py\`" >> README.md

 Commit four.py and README.md

git add four.py README.md
git commit -m "Add update-4 and README.md"

 Switch back to master

git checkout master

 Merge update-3 into master

git merge update-3

 Merge update-4 into master (fix conflicts if any)

git merge update-4

 Resolve merge conflicts in README.md as instructed

 Check the status

git status

 Commit the remaining files

git commit -m "Resolve merge conflicts in README.md"



 to create a branch named update-5

git branch update-5

 to create five.py file with content

echo "print('five')" > five.py

 Edit README.md for update-5

echo " Hello, venkat" > README.md
echo "To run \`update-3\`, execute \`python3 three.py\`" >> README.md
echo "To run \`update-4\`, execute \`python3 four.py\`" >> README.md
echo "To run \`update-5\`, execute \`python3 five.py\`" >> README.md

 Commit five.py and README.md

git add five.py README.md
git commit -m "Add update-5 and update README.md"

 Switch back to master

git checkout master


 to create a new branch named update-6

git branch update-6

 to create six.py file with content

echo "print('six')" > six.py

 to create README.md for update-6

echo " Hello, venkat" > README.md
echo "To run \`update-3\`, execute \`python3 three.py\`" >> README.md
echo "To run \`update-4\`, execute \`python3 four.py\`" >> README.md
echo "To run \`update-6\`, execute \`python3 six.py\`" >> README.md

 Commit six.py and README.md

git add six.py README.md
git commit -m "Add update-6 and update README.md"

 Switch back to master

git checkout master

 Merge update-5 into master

git merge update-5

 Switch to update-6 branch

git checkout update-6

 Rebase update-6 from master 

git rebase master

 Resolve merge conflicts in README.md as instructed

 Check the status

git status

 Commit the remaining files

git commit -m "Resolve merge conflicts in README.md"

 Switch back to master

git checkout master

 Merge update-6 into master

git merge update-6


