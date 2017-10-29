# Docker image for smtpapi-ruby
Running smtpapi-ruby in a Docker container for testing.

## Quickstart
1. [Install Docker](https://docs.docker.com/engine/installation/) and [docker-compose](https://docs.docker.com/compose/install/) on your machine.
2. Put your code in `./src`
3. Run `docker-compose run mock-server`
4. Run your code with `ruby your_code.rb` inside the container

## Examples
1. Run `docker-compose run mock-server`.
2. In your container, run ``ruby examples/example.rb``


#docker build -t smtpapi-ruby .
