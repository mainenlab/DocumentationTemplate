# Documentation Template

This repository provides a documentation template on how to do things in the lab. To create a repository about something concrete (like inventory), simply start a new repository with the same files as here.

## Developer guide

The markdown files in docs/ directory are used to generate the documentation website. To generate the site locally, simply do:

```
mkdocs serve
```

in the directory of this repository. Once you are sure of the changes simply do `mkdocs gh-deploy` to deploy the modified site. Always remember to also commit and push the changes to the source file in the git repository.

As a set-up, it is recommended to have:

- [git](http://rogerdudler.github.io/git-guide/)
- [mkdocs](https://www.mkdocs.org/)
- [atom](https://atom.io/) text editor to edit markdown files as well as to simplify working with git

## User guide

Simply check out the website linked at the top of this page: use the Search function of the website! If something does not appear in the docs or you are experiencing an issue, simply go to the Issues tab and open a new one. You will be guided by templates. Maintainers of the repo can then label the issue and organize labels.
