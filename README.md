# logstash-gelf-api-plugin

Allows Jenkins to log in JSON format. Edit $JENKINS_HOME/logging.properties:
```
java.util.logging.FileHandler.formatter=biz.paluch.logging.gelf.jul.GelfFormatter

```

For extended properties see: https://logging.paluch.biz/examples/jul-json.html
