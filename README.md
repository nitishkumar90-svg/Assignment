# Assignment

Q. Assuming that you aren't sure whether you're currently inside of a Git repository, write the command (or commands) that will give you this information.
git status

Q. Assuming that you are currently within a Git repository, write the command (or commands) that will create a new file named 'hello-world.txt' then stage and commit it.
touch hello-world.txt
git add hello-world.txt
git commit -m "hello-world.txt created!!"

Q. Assuming that you are currently within a Git repository that contains a file named 'README.md', write the command (or commands) that will display any uncommitted changes made to this file.
git diff README.md

Q. Assuming that you are currently within a Git repository that includes several commits, write the command (or commands) that will display the changes from the commit with the ID of abc123.
git show abc123

Q. Assuming that you are currently within a Git repository that includes multiple commits, write the command (or commands) that will display the IDs and commit messages for the 3 most recent commits.
git log -3