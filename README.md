# 反映方法

```sh
echo "SLACK_WEBHOOK_URL=https://..." > .env
```

aws cliにmaximumのadmin権限でログイン

それがデフォルトのProfileになっていることを確認してから

```bash
sls deploy
```
