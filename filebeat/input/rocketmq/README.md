```yaml
filebeat.inputs:
  - type: rocketmq
    name_server_addrs:
      - 10.4.27.13:9876
      - 10.4.27.14:9876
    group_name: "CID_filebeat"
    topic: "TopicTest"
```
