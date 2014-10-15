# Docker container for Couchbase Community Edition

Docker container for the [Couchbase server](http://www.couchbase.com) community edition.

# Usage

Currently possible to start only as a cluster with a single node (more options coming).

```
docker run -d -p 8091:8091 mihahribar/couchbase
```

Then open in browser <DOCKER HOST IP>:8091 to customize the cluster.
