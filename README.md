# git-exercesice
1 new folder demo
2 new repo ..... git exercesice
3 add few files  demo1 to demo5
   git init
   git add .
   git status
   git commite -m " add demo files"
   git branch -m main
   git remote add origin git@github.com:ashishvalu/Git-Exercesice.git
   git push origin main

5 Commit your first change
   git status
   git add .
   git commit -m "add git commands"   #demo file1  add commands
   git push origin main

7&8 git checkout -b dev
   Create 2 new file
   demo7
   demo8

10 11 Commit changes to `dev` branch
    git status
    git add .
    git commit -m "add 2 new files dev branch"
    git push origin dev

12.
   git checkout main
   git merge main dev

13. Push merged changes to origin
git push origin main

14. Checkout to `dev`
git checkout dev

15. Update existing file
   git status
   git add .
   git commit -m "update files demo2"
   git push origin dev

17. Checkout to `master`
   git Checkout main

18. Update same file you changed last. Also change same line with differnet changes
     //demo1 update

19. Commit changes and push to origin master
      git status
      git add .
      git commit-m "update files"
      git push origin main


20. Checkout `dev` branch
    git checkout dev

21. Rebase dev with master
    git rebase dev main
    git push origin main

  22. Rebase Abort
    git rebase --abort

23 Again Rebase with dev26. Force Push
   git rebase dev main
   git push origin main

24.Fix Conflict
///resolve the conflict
  git add .
  git commit -m "Fix Conflict"
  git rebsae -- continue
  git push origin

25. Rebase continue
git rebase continue

26. Force Push
git push -f origin main
