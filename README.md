### Git-names

Hopefully this helps you git good with git :)

1) Clone the repo with the command ``` git clone git@github.com:angel-721/git-names.git ```
2) Make a branch named after your favorite food ``` git checkout -b your-favorite-food ```(no spaces)
    - example) ``` git checkout -b hawaiian-pizza ```
3) Run ``` git branch ``` to ensure that you are in the right branch
4) Edit with neovim the names.txt file and add your name with a fun fact about yourself at the very last line
    - example) ``` Angel - I can run a mile in 6 minutes and 30 seconds ```
5) Stage your changes with git add  ```git add names.txt ``` 
6) Commit your changes with git commit with a message saying add your name to names.txt ```git commit -m "insert message here" ``` 
    - example) ```git commit -m "add Angel to names.txt" ```
7) Switch back to the main branch ``` git checkout main ```
    - You don't need -b here since main already exists as a branch
8) Pull latest changes from main just in case ``` git pull ```
9) Merge your changes from your branch by running ``` git merge name-of-your-branch ```
   - example) ```git merge hawaiian-pizza ```
   - This will get the changes you made in your branch and bring them to main
  
10) Push with your upstream set to main ``` git push -u origin main ```
