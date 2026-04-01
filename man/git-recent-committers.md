git-recent-committers(1) -- Show a list of recent committers.
## SYNOPSIS
git recent-committers [-n DAYS]

## DESCRIPTION
Lists authors who have made commits in the last N days, along with their commit count.

## OPTIONS

-n DAYS  
: Number of days to look back.

## ENVIRONMENT

GIT_RECENT_COMMITTERS_DAYS  
: Default number of days if 7 is not provided.

## EXAMPLES

git recent-committers  
git recent-committers -n 10  

## SEE ALSO

git-log(1), git-shortlog(1)
