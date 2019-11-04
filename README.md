# Babsy site

## About
Static website for babsy.me

## Deploy
- Edit files inside `site` directory.
- Commit changes
- Push changes to github
- CircleCI will deploy changes in 2-3 minutes

## How does it work?
See hidden files `.circleci/config.yml` and `.s3-website.json` for more information.
Uses NodeJS packages to transfer the files to an AWS S3 bucket (cloud hosting).
CircleCI is a continous deployment service that reads the config.yml and executes the tasks there on git push
