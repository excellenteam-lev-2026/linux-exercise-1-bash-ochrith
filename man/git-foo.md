# git-foo

## SYNOPSIS

git foo [options]

## DESCRIPTION

The `git-foo` command lists the most frequently modified files in the current Git repository.
It is useful for quickly identifying files with the most changes, which can help in code review
or understanding areas of high activity in the project.

## OPTIONS

-n <number>      Number of files to display (default: 7)
-e               Sort files in descending order by number of modifications
-h               Display help and exit

## EXAMPLES

# Show the 7 most modified files (default)
git foo

# Show the 5 most modified files
git foo -n 5

# Show all files sorted by descending number of modifications
git foo -e
