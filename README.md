# docker-evologger

run [Evo Logger](https://github.com/freeranger/evologger) in a docker container

See freeranger's instructions for configuring evologger

### Quickstart

1. Clone the repo
2. Edit and rename the `config/config-default.ini` file to `config/config.ini`
3. create the `output` directory
4. run `docker run -v "$(pwd)"/config/config.ini:/evologger-master/config.ini -v "$(pwd)"/output:/output -d evologger`
