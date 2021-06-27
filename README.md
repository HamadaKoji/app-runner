# app-runner

jaws-ug コンテナ支部 #19

CopilotとApp Runnerの欲張りセット

## 事前確認

```
copilot --version
```

## App Runner作成

App Runner用設定内容

- Service-type:Request-Driven Web Service
- Application Name:jaws-ug-app5
- Service Name:jaws-ug-app5-svc

```
copilot init
```

URLが出るので、

## パイプラインの作成

```
copilot pipeline init
copilot pipeline update
```

BuildSpec.ymlが自動的に作成される。

作成されたファイルをコミットしてプッシュしておく。




