## 0.5.5

* (New) Add custom path
* (New) Add support for custom s3 endpoint created from release name
* (New) Allow key and salt to be specified in plain text and converted to hex by chart

## 0.5.3 (2020-03-03)

* (Fix) indentation typo in ingress-health.yaml

## 0.5.2 (2020-03-02)

* (New) `ingress.health.whitelist` Comma separated string of CIDR addresses that are allowed to access `/health` url of imgproxy

## 0.5.1 (2020-02-25)

* (New) imgproxy v2.10.0
* (Fix) unnecessary empty environment variables were removed
* (Fix) quoted templated strings refactoring
