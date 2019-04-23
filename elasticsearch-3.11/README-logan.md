# Elasticsearch

## Image Build
```bash
docker build --build-arg OSE_ES_URL=https://portal.test.logan.xiaopeng.local/nexus/service/local/repositories/public/content/io/fabric8/elasticsearch/openshift-elasticsearch-plugin/5.6.13.7/openshift-elasticsearch-plugin-5.6.13.7.zip -f Dockerfile.centos7 -t xpmotors/origin-logging-elasticsearch:v3.11.1 .
```

