# About this repository

The `academic-kickstart` repository provides two things:

- A basic setup of a website using the `academic` theme
- The `academic` theme loaded as a submodule on the `themes/academic` path

This repository is a fork of the `academic-kickstart` repository.

The `master` branch of this repository should always point to the latest `master` of the original repo.

If cloning for the first time, add the remote to the original repo:
```bash
git remote add original https://github.com/sourcethemes/academic-kickstart.git
```

The `napulen.github.io` branch of this repository has the changes introduced for generating the website at https://napulen.github.io and it is the default branch

# Migration to newer version of academic

When migrating to a newer version of the `academic` repository.

Sync this `master` and get it up to date
```bash
git checkout master
git pull original master
```