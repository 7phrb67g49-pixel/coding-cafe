# Lab 4 Questions

# Coding Café

Lab work for Coding Café, FM102.

**Name:** Jay Mangukiya

**Roll number:** U20260107

## Contents

- `lab1/` — terminal
- `lab2/` — variables, types, operations, I/O
- `lab3/` — conditionals and loops
- `lab4/` — Git and GitHub

## Question 1
`--global` means that the Git configuration is saved for my user account and applies to all Git repositories on this computer. If I leave it out, the configuration is normally applied only to the current repository.

## Question 2
`ls -a` showed the hidden `.git` directory. This directory contains Git's internal information, including the repository's history, configuration, references, and objects. It is what allows Git to track the repository.

## Question 3
Git was offering roughly 7 files and folders to track in my initial `git status`. Some entries, such as `.DS_Store`, were not files I had intentionally created; they are system-generated files.

## Question 4
After creating `.gitignore`, files such as `.DS_Store` that matched the ignore rules disappeared from the `git status` list. Git was therefore no longer offering those ignored files to be tracked.

## Question 5
`.gitignore` should be committed because it is part of the repository's configuration and tells Git which files should not be tracked. It should not be ignored because other people who clone the repository also need the same ignore rules.

## Question 6
`README.md` moved from the “Untracked files” section to “Changes to be committed” after I ran `git add README.md`. In the three-places model, it moved from the working tree into the staging area, ready to become part of a commit.

## Question 7
After the commit, Git printed that 6 files had changed and reported 2567 insertions. It also listed the files that were created by the commit.

## Question 8
The first seven characters of a commit hash are an abbreviated commit ID. They provide a shorter way to identify a specific commit without having to type the entire hash.

## Question 9
The four-step Git loop is edit, stage, commit, and repeat. I first make changes to the files, use `git add` to stage those changes, use `git commit` to save them in the repository history, and then repeat the process for future changes.

## Question 10
`README.md` gets a special name because GitHub automatically recognizes it and displays it prominently on the repository's front page. It acts as the introduction or guide to the repository, so it is placed at the root of the project where GitHub can easily find it.

## Question 11
`gh auth login` authenticated my GitHub account through GitHub CLI and stored the authentication credentials securely. Because Git can use that authentication when communicating with GitHub, I do not have to enter my GitHub password every time I push.

## Question 12
The GitHub repository front page shows the contents of `README.md` as formatted text. GitHub does this because `README.md` is automatically recognized as the repository's main introductory documentation.

## Question 13
No, `git push` did not change my local history. It copied my existing local commits to GitHub, while the commits and their hashes remained the same locally.

## Question 14
A private repository exists on GitHub but its contents are restricted to the owner and people who have been given access. A repository that does not exist on GitHub has no online repository at all, so there is nothing for others to access or collaborate on.

