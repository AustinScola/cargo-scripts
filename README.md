# Cargo-scripts 

This repo contains scripts common for cargo projects.

It is intended to be used as a git submodule at the relative path `scripts` within a git reposity
that is a cargo project.

# Instructions

To add `cargo-scripts` to a git repository run:
1. `git submodule add https://github.com/AustinScola/cargo-scripts.git scripts` from the repository.
2. `cd <repo-root>/scripts`
3. `git checkout <tag>`
4. Optionally add `PATH_add scripts` to `<repo-root>/.envrc` to add the scripts to the PATH using
`direnv` when in the repo.
