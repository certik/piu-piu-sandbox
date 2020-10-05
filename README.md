# piu-piu-sandbox
a repository to play with a tool for generating tweets in comments of a PR, to be published upon merging. it is meant for the [fortran-lang/fortran-lang.org](https://github.com/fortran-lang/fortran-lang.org) GitHub repo.

# how to use
just submit a PR and write some comments.

#tweet `text` will:
1. remove a previous tweet, if it exists.
2. add a new tweet to be published by the CI once the PR is merged.

#untweet will remove the tweet.

Some text.
