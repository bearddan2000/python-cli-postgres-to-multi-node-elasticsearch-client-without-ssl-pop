# python-cli-postgres-to-multi-node-elasticsearch-client-without-ssl-pop

## Description
Reads a multi node cluster for data in `pop-demo` document.

Uses `pop` table then covverts it to json for
elasticsearch to use.

## Tech stack
- python
    - psycopg2
    - sqlalchemy
- elasticsearch
- kibana
- postgres

## Docker stack
- python
- elasticsearch
- kibana
- postgresql:alpine

## To run
`sudo ./install.sh -u`

## To stop (optional)
`sudo ./install.sh -d`

## For help
`sudo ./install.sh -h`

## Credit
- [Docker setup](https://lynn-kwong.medium.com/all-you-need-to-know-about-using-elasticsearch-in-python-b9ed00e0fdf0)
- [Search setup](https://www.elastic.co/guide/en/elasticsearch/client/python-api/master/examples.html)