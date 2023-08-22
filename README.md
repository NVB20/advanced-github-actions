# advanced-github-actions
- pull docker image only after the push workflow is completed

can change the push event to only if Dockerfile is changed
on:
  push:
    path:
      - Dockerfile
