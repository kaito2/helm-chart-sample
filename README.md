## Helm のバージョン管理素振り

Chart 作成

```
$ helm create sample
Creating sample
```

Package 作成

```
$ helm package sample
Successfully packaged chart and saved it to: /Users/kaito2/ghq/github.com/kaito2/helm-chart-sample/sample-0.1.0.tgz
```

```
$ mkdir charts
$ mv sample-0.1.0.tgz charts
```
