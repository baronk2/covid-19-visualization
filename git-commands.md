# A1: Basic Tools: Part I: Command Line [9 tasks to complete]

The purpose of this file is for you to demonstrate your knowledge of working with the terminal. Following each prompt below, write the line of code that you used on the terminal to accomplish the task.

```bash
# (1) Print your working directory [complete: YES]
pwd

# (2) List the files in your current directory [complete: YES]
ls

# (3) Change your directory to your info201 root directory.  This should be `~/Documents/info201`. [complete: YES]
cd ~/documents/Kevin/School/University_Of_Washington/Informatics/2022-2023/Autumn_2022/Info_201/info201

# Resubmission Note: I had been two folders down from the `info201` root
# directory at the time that I was working on prompt #3, so `cd ../..`
# seemed like the appropriate command. I understand that the hard path
# is better. Thank you!

# (4) Use the git command `clone` to clone your A1 assignment repository from GitHub to your `assignments` directory [complete: YES]
git clone https://github.com/info201b-au2022/a1-baronk2


# (5) Using a *relative path*, change your directory to inside the repository you just cloned [complete: YES]
cd a1-baronk2

# (6) Find the file "covid-example-2" with 'cd' commands. What is the *absolute path* to this file? [complete: YES]
~/documents/kevin/school/university_of_washington/informatics/2022-2023/Autumn_2022/info_201/info201/assignments/a1-baronk2/images/COVID-19-Visualizations/covid-example-2.png

# Resubmission Note: I thought for a while when working on this prompt
# the first time about whether to include the file name. I read "What is
# the *absolute path* to this file" the complete folder path to redirect "to"
# the file. I would have read "What is the *absolute path* ***of*** this
# file?"  as intended to include the name and extension of the file in the
# path. In the future, I will read "path to the file" as including the
# file name and extension. Thank you!

# (7) Use the git command `add` to add all of your changes that you've made to this and other files (if any) [complete: TBC (YES)]
cd ../..      # To get to appropriate folder
git status    # To check status of repository
# Save this file
git add .
#0r
git add git-commands.md   #Since this is the only file modified

# (8) Use the git command `commit` to commit your changes. Be sure to include a *descriptive message* [complete: TBC (YES)]
git commit -m 'Complete Assignment 1 git-commands instructions'

# (9) Using the git command `push` to push your changes up to GitHub [complete: TBC (YES)]
git push

```
