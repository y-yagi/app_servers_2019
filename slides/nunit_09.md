### 設定

* 3000番ポートにリクエストがきたら全てRackアプリケーションを実行するJSON

```json
{
  "listeners": {
    "*:3000": {
      "pass": "applications/ruby_app" }
  },
  "applications": {
    "ruby_app": {
      "type": "ruby",
      "working_directory":
      "/www/ruby/nginx-unit",
      "script": "config.ru"
    }
  }
}
```
