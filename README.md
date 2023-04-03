# EX-1
REBASE vs. MERGE - training by simulating work on the project with min. 2 people

The idea of this repository was to simulate work on the project by 2 people minimum - Had 2 GIT opened for each individual (A - master, A' - master fix)), (B-fix)
1. first step was to create buggy .txt files - 1 commit master (A)
2. second step was to clone the repository to a copy folder, adjust fixes, add another text file and suggest changes by adding "readme" file - 1 fix commit (B)
3. third step was to pull fixes to different branch seperated from "master" branch, add more files, adjust suggested changes with mistakes on purpose - master-fix commit (A')
4. forth step was to pull to B what was done in A' and fix mistakes
5. fifth step was to add another text file in A' with a lot of mistakes and push new commit before fixes in B were pushed to the repository - master-fix commit 2 (A')
6. sixth step was to try to push fixes to remote repo while remote repo was already updated - this was done to train REBASE - master-fix commit 2 (B)
7. seventh step was to fix mistakes in added text file that was pulled by doing REBASE, push it to repo - master-fix commit 3 (B)
8. eight step was to pull fixes to A' and MERGE it to master branch A
