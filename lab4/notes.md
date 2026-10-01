# Lab 4 Questions

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

