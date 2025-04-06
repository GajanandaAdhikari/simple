# simple
Simple implementation of CI/CD - docker for DevOps.



# Jekyll Site CI

This project sets up Continuous Integration (CI) for a Jekyll site using GitHub Actions. The site is automatically built whenever changes are pushed to the `master` branch or a pull request is created.


## Features

- Automated Jekyll site builds on push and pull request events.

- Uses Docker for a consistent build environment.


## Technologies Used

- **Static Site Generator**: Jekyll

- **CI/CD**: GitHub Actions

- **Containerization**: Docker


## Workflow Configuration

The CI workflow is defined in `.github/workflows/ci.yml`. It triggers on pushes and pull requests to the `master` branch and builds the Jekyll site using the `jekyll/builder` Docker image. 
