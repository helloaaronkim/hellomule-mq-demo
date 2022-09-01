## Anypoint MQ Demo

### Queue setting
![](https://i.imgur.com/NSuwKX6.png)

### Canvas example
Using subscriber, client is able to ger the queued messages (payload, attributes)

![](https://i.imgur.com/hAp5L2p.png)

**Sample query for publishing message**
```
curl -X POST \
  http://hellomule-mq-demo.jp-e1.cloudhub.io/mq/100 \
  -H 'content-type: application/json' \
  -d '[  {
    "body": "Welcome to Hellomule!"
  }
]'
```

**Docs**
- https://docs.mulesoft.com/mq/