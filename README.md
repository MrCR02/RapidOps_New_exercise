# RapidOps_New_exercise

# RapidOps_New_exercise

Q1: git clone https://github.com/MrCR02/RapidOps_New_exercise.git
Q2: git checkout -b dev
    git add .
    git commit -m "message"
Q3: git branch branch1
        git checkout branch1
        git add .
        git commit -m "message"
    git branch branch2
        git checkout branch1
        git add .
        git commit -m "message"
Q4: git checckout branch1
        git add .
        git commit -m "message"
    git checckout branch2
        git add .
        git commit -m "message"
Q5: git commit --amend -m "changing branch 1 commit message"
    git commit --amend -m "changing branch 2 commit message"
Q6: git push origin dev
    git push origin branch1
    git push origin branch2
Q7: git merge branch1
    git merge branch2
Q8:
    git checkout branch2
        git add .
        git commit -m "message"
    git checkout branch1
        git stash pop .
        git add .
        git commit -m "message"

Q9: git branch feature1
    git branch feature2
    git push origin feature1
    git checkout feature2
        git pull origin feature1
    git checkout dev
        git merge feature1
    git push origin feature2
    git rebase dev
    git checkout dev
        git merge feature2
