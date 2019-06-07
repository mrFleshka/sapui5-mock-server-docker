# Info

SAPUI5 Mock Server practice (For SAPUI5 version: 1.65.1).

[Documentation](https://sapui5.hana.ondemand.com/#/topic/3a9728ec31f94ca18a7d543ce419d85d)

Used with docker (nginx proxy-pass + node server).
 
# Run

For start add network in docker (used for custom windows network with routing to virtual machine):

```bash
docker network add develope
```

Then just start docker:

```bash
docker-compose up
```

Demo site available at [mock-server.sapui5.test](http://mock-server.sapui5.test/index.html)