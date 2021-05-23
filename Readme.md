# My first Kafka project

## Docker kafka setup

From https://docs.confluent.io/platform/current/quickstart/ce-docker-quickstart.html#ce-docker-quickstart

$ curl --silent --output docker-compose.yml \
 https://raw.githubusercontent.com/confluentinc/cp-all-in-one/6.1.1-post/cp-all-in-one/docker-compose.yml

Start Confluent Platform with the -d option to run in detached mode:

$ docker-compose up -d

Navigate to the Control Center web interface at http://localhost:9021

## Python Development

From https://kafka-python.readthedocs.io/en/master/usage.html

Setup env

‘virtualenv ccloud-venv -p /usr/local/bin/python3.9
source ./ccloud-venv/bin/activate
pip install -r requirements.txt‘

Run consumer with

python consumer.py

Run producer with:

python producer.py

# Test producer
