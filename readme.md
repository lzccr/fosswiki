# FossWiki

Everything about FOSS. From what it is, how to use it, to detailed guide on configuration and installation that is beginner-friendly.

# Contribution

- Submit an issue on the official [GitHub Repo](https://github.com/lzccr/fosswiki) for any FOSS you want to add.

- Even better? Submit a Pull Request. See the guide for pull requests below.

# Website

https://lzccr.github.io/fosswiki

# Pull Requests

First, fork this repository.

Then, clone it and create a new branch using

```shell
git clone git@github.com:<your-username>/fosswiki.git
cd fosswiki
git checkout new-branch
```

## For adding a FOSS, or change of documentation

Add/Change the `.md` file under `docs` folder, then submit a pull request.

GitHub Actions should automatically generate a file under `site`.

## For making changes to the config files

Change the files, then submit a pull requests.

## What should not be changed without creating an issue first:

Under `site`:

`assets/javascripts`, `assets/stylesheets`, and `search`

(Since they are generated automatically)
