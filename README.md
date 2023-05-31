# What inside
This repo provide a Docker image with RUST nightly installed and some dependencies.

## RUST version
nightly-2023-02-26

## Installed packages
- clang-dev
- cargo grcov
- cargo watch
- cargo sscache
- cargo diesel

# How to use
The result docker image can be found at `ghcr.io/climateseed/rust-buildpack:latest`

## Updating
The docker image is updated via github workflow, see `.github/workflows/publish.yml`