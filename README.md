# my-first-cicd

![CI](https://github.com/TEgor1212/my-first-cicd/actions/workflows/ci.yml/badge.svg)

First CI/CD pipeline — testing GitHub Actions with a simple workflow.

This repository contains a minimal GitHub Actions workflow that runs on every push, demonstrating the basics of continuous integration.

## Workflow

- Trigger: `git push`
- Action: runs `echo "Hello, World!"` on the latest Ubuntu runner