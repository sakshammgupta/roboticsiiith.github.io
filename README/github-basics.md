# Github Basics to contribute to this repository





### Cloning the repository (to be done only once)

To clone the repository, type the following commands in your terminal

```bash
# Clone repository
git clone https://github.com/RahulSajnani/RRC-new-website.git -b project-pages
# Enter repo
cd RRC-new-website
```



### Pull changes (to be done everytime)

Before you make any changes pull the changes

```bash
# Pull
git pull origin project-pages
```



### Adding paper (to be done everytime)

Follow the [adding paper markdown](./Adding-paper.md) to add a paper. Once you have created the paper file you can do a git status to check your changes. Commit these changes.

```bash
# Check the files that are changed
git status
# Add the files that you have changed (example - git add _pages/<paper>.md)
git add <filename>
# Commit your change (example - git commit -m "Add paper DRACO")
git commit -m <message-in-quotes >
# Push your commit to branch
git push origin project-pages
```


