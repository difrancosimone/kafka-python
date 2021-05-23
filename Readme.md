# Docker kafka setup

From https://docs.confluent.io/platform/current/quickstart/ce-docker-quickstart.html#ce-docker-quickstart

$ curl --silent --output docker-compose.yml \
 https://raw.githubusercontent.com/confluentinc/cp-all-in-one/6.1.1-post/cp-all-in-one/docker-compose.yml

Start Confluent Platform with the -d option to run in detached mode:

$ docker-compose up -d
