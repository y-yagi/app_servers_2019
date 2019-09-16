### NGINX Unit

* リクエストが来る毎にそれを処理する為のプロセスが実行される
  * プロセスが起動済みの場合当然使い回し
  * 詳細: [Introducing NGINX Unit \- NGINX](https://www.nginx.com/blog/introducing-nginx-unit/)
* リクエストがあったパス毎にアプリケーションを使い分ける事が出来る
  * 一個のNGINX Unitで複数言語のアプリケーションを使える
