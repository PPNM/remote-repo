>>Collaboration Task

>>My collaborator - Ko Bhone Aung Kyaw 

git clone https://github.com/Dev-BhoneAK/git-assignment.git
cd git-assignment/
git branch -a
ls
echo "adding a new line by ppnm" >> feature.txt 
ls
git status
git add feature.txt 
ls
echo "1 sep 24 adding a new files" > phuephuenyomyint.txt
ls
git status
git add phuephuenyomyint.txt 
git commit -m "phuephuenyomint commit on sep 1"
git status
git log
git remote add upstream https://github.com/Dev-BhoneAK/git-assignment.git
git remote -v
git push -u origin main
history
