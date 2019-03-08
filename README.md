# Documentation Template

This repository provides a documentation template on how to do things in the lab. To create a repository about something concrete (like inventory), simply start a new repository with the same files as here.

## User guide

Simply check out the website linked at the top of this page: use the Search function of the website to find things! If something does not appear in the docs or you are experiencing an issue, simply go to the Issues tab and open a new one. You will be guided by templates. Maintainers of the repo can then label the issue and organize labels.

## Developer guide

The markdown files in docs/ directory are used to generate the documentation website. To generate the site locally, simply do:

```
mkdocs serve
```

in the directory of this repository. Once you are sure of the changes simply do `mkdocs gh-deploy` to deploy the modified site. Always remember to also commit and push the changes to the source file in the git repository.

The set of markdown files to be used for the website is described in the `nav` section of the mkdocs.yml configuration file.

### Set-up for development

As a set-up, it is recommended to have:

- [git](http://rogerdudler.github.io/git-guide/)
- [mkdocs](https://www.mkdocs.org/)
- [atom](https://atom.io/) text editor to edit markdown files as well as to simplify working with git

Git and mkdocs are absolutely necessary, atom is optional: any text editor will do.

To install mkdocs and the material theme (used in this site), simply do:

```
pip install mkdocs
pip install mkdocs-material
```

in a terminal.
