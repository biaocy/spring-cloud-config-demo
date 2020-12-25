# spring-cloud-config-demo
Spring cloud config demo

## Run
### Server
```bash
mvn -pl server spring-boot:run
```
Test server:
```bash
curl http://<user>:<pass>@localhost:8888/client/dev/master
```

### Client
```bash
mvn -pl server spring-boot:run
```
Test client:
```bash
curl http://localhost:8080/whoami/bill
```
