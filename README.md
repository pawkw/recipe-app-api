# recipe-app-api
Python3/Django recipe app in a Docker container.

# Dev

## Build

Change to the root directory of the app ('recipe-app-api') and run:
`docker-compose build`

## Run linting

To run linting, use:
`docker-compose run --rm app sh -c "flake8"`
