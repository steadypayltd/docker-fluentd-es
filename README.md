# Fluentd and Elasticsearch

This is based on the [image](https://github.com/kubernetes/kubernetes/tree/master/cluster/addons/fluentd-elasticsearch/fluentd-es-image).

Also includes the following plugins:
* fluent-plugin-kubernetes_metadata_filter
* fluent-plugin-elasticsearch
* fluent-plugin-systemd
* fluent-plugin-detect-exceptions
* fluent-plugin-prometheus
* fluent-plugin-multi-format-parser
* fluent-plugin-rewrite-tag-filter
* fluent-plugin-concat