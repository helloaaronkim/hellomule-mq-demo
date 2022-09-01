## Anypoint MQ Demo
```
Sample query for publishing message
```
```
curl -X POST \
  http://hellomule-mq-demo.jp-e1.cloudhub.io/mq/100 \
  -H 'content-type: application/json' \
  -d '[  {
    "body": "Welcome to Hellomule!"
  }
]'
```
