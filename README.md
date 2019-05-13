Minimal example for ug report using consul service discovery on kubernetes

## Steps to reproduce

- You need a running consul `docker run -p 8500:8500 consul:1.2.4`
- Checkout the code
- Start `./gradlew run`
- Call `http://localhost:8080/health`