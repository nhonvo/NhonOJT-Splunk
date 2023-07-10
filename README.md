
```bash

docker run -d -p 8000:8000 -p 8088:8088 -e "SPLUNK_START_ARGS=--accept-license" -e "SPLUNK_PASSWORD=Password_Here" --name splunk splunk/splunk:7.3.4
```
