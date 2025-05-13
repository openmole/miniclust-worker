
# MiniClust Worker

To deploy a [miniclust](https://github.com/openmole/miniclust) worker on a computer, just clone this repo.
```
git clone https://github.com/openmole/miniclust-worker.git
```

Edit the config.yml file, and change the service url, key and secret:
```
minio:
  url: https://babar.openmole.org
  key: key
  secret: secret
```

Then run:
```
docker compose up -d
```

Prerequisite:
  - docker
  - docker compose

