
# MiniClust Worker

To deploy a worker on a computer, just clone this repo.
```
git clone https://github.com/openmole/miniclust-worker.git
```

Edit the config.yml file, and change the service url, key and secret:
https://github.com/openmole/miniclust-worker/blob/main/config.yml#L3-L5

Then run:
```
docker compose up -d
```

Prerequisite:
  - docker
  - docker compose

