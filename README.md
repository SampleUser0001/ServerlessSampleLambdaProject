# ServerlessSampleLambdaProject
serverless frameworkを使ってみる

## デプロイ

``` sh
sls deploy -v --stage stg
sls deploy -v --stage dev
```

## 削除

``` sh
sls remove -v --stage stg
sls remove -v --stage dev
```

## 備考

- functions-関数名-enabledがfalseの関数は、デプロイされないだけでなく、eventsも設定されない。