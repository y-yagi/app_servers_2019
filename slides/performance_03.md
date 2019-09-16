### パフォーマンス

* ベンチマークは複数のパターン(JSONを返す、データベースに対して1つSQLを実行する、等々)で実施されている
  * データベース(MySQL、PostgreSQL、MongoDB、等々)やアプリケーションサーバも複数パターン(Puma、unicorn、等々)で行っている
* Full-stack frameworksだけじゃなくMicro frameworksも対象になっている
  * そもそも素のRackもFrameworkに含まれている
