# [Labs] We don't assign issues

This repository contains a GitHub workflow allowing to send a message in an issue by simply attaching a "we don't assign issues" label to the issue.

The label will be automatically deleted right-after.

You can see the process in https://github.com/Open-reSource/labs-we-don-t-assign-issues/issues/3.

<img width="922" alt="Screenshot 2023-05-05 at 10 38 36" src="https://user-images.githubusercontent.com/17381666/236413271-12b7b2f2-12b1-4498-99d0-19db8b4b97d8.png">

## Steps to install it in your repository

1. Create a new "we don't assign issues" label in your repository

<img width="1227" alt="Screenshot 2023-05-05 at 10 32 09" src="https://user-images.githubusercontent.com/17381666/236412159-a6331898-f1d1-4ca3-bfa8-0f2124c5c53b.png">

2. Create a new workflow in `.github/worflows` (name doesn't matter)
3. Copy the content of https://github.com/Open-reSource/labs-we-don-t-assign-issues/blob/main/.github/workflows/we-don-t-assign-issues.yml and adapt the label name, and the comment sent to the users.

## Sponsors of Open {re}Source

<p align="center">
  <img src='https://cdn.jsdelivr.net/gh/Open-reSource/sponsors/sponsors.svg'/>
</p>
