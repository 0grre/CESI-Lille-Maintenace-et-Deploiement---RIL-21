# git-flow

Git Flow is a worflow allowing to work with features, bugfixes, releases and keep a clean working flow.

To follow this kinf of git-flow => https://www.atlassian.com/fr/git/tutorials/comparing-workflows/gitflow-workflow#:~:text=Gitflow%20est%20un%20workflow%20Git,de%20d%C3%A9veloppement%20continu%20et%20DevOps. you can setup some tool like below :

## Setup the git-flow

Use https://github.com/petervanderdoes/gitflow-avh

### Installation

See the Wiki for up-to-date [Installation Instructions](https://github.com/petervanderdoes/gitflow-avh/wiki/Installation).

### Some commands

```
git flow init

git flow feature start "name_of_the_feature" #to start a feature branch
git flow bugfix start "name_of_the_bugfix" #to start a bugfix branch

git flow hotfix start "version" #to start a hotfix branch like 1.0.0-1 (semantic versioning)

git flow release start "version" #to start a release branch like 1.0.1 (semantic versioning)

# next commands

git flow feature publish

```

## Semantic versioning 2.0

Read the [documentation](https://semver.org/lang/fr/#gestion-s%C3%A9mantique-de-version-200)
