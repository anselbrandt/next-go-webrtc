# Next Go WebRTC

Automatically negotiates a WebRTC connection and starts streaming video from file after receiving an offer via MQTT

Using the Eclipse public test MQTT broker service:

```
mqtt.eclipseprojects.io

1883 : MQTT over unencrypted TCP
8883 : MQTT over encrypted TCP
80 : MQTT over unencrypted WebSockets (note: URL must be /mqtt )
443 : MQTT over encrypted WebSockets (note: URL must be /mqtt )
```

### Request/Response Pattern

https://github.com/eclipse/paho.golang/issues/7

Extension for Request/Response:

https://github.com/eclipse/paho.golang/blob/master/paho/extensions/rpc/rpc.go

Example of extension implementation:

https://github.com/eclipse/paho.golang/blob/master/paho/cmd/rpc/main.go
