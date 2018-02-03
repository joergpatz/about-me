# about-me
Source code for my personal website

## how-to-subtree

```
//initialize
git subtree add --prefix out --squash git@github.com:joergpatz/joergpatz.github.io.git master
// pull updates from remote subrepo
git subtree pull --prefix out --squash git@github.com:joergpatz/joergpatz.github.io.git master
//split changes to an extra branch
git subtree split --prefix out --branch out/changes
//push the changes to subrepo
git subtree push --prefix out --squash git@github.com:joergpatz/joergpatz.github.io.git master
```
