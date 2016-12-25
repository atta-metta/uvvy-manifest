Uvvy
====

This is top level project for Uvvy, peer-to-peer communication client.

This project uses repo tool, replacing the old clunky submodules.

To prepare for build, clone this repository using `repo` tool:

```
mkdir -p uvvy
cd uvvy
repo init -u https://github.com/berkus/uvvy-manifest.git
repo sync
```

Get Google's "Repo" tool

Repo is a tool by Google used for managing multiple git repositories. We use multiple subprojects, and Repo will fetch all of them and place them in the correct subdirectories for you. [Get repo here.](http://source.android.com/source/downloading.html#installing-repo)
