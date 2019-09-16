### iodine

* 実装はRubyじゃなくてC
* 元々[boazsegev/facil.io](https://github.com/boazsegev/facil.io)というCで作ったウェブアプリケーションがあって、それをベースにRubyから使う為のインターフェースを追加しただけ、らしい
* Pub/SubのストレージRedisを使用出来るが、Redisとの接続処理等も全部iodine内でCで実装されている
  * HTTPに関する処理もiodine内で全てCで実装されている
  * runtime dependencyが一個もない: [iodine](https://rubygems.org/gems/iodine)
