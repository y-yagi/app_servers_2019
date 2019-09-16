### Falcon

* https://github.com/socketry/falcon

<small>
"Falcon is a multi-process, multi-fiber rack-compatible HTTP server built on top of [async], [async-io], [async-container] and [async-http]. Each request is executed within a lightweight fiber and can block on up-stream requests without stalling the entire server process. Falcon supports HTTP/1 and HTTP/2 natively."
</small>

* リクエストを処理するのにFiberを使用し、サーバプロセス全体の処理を止めないようにしているから高速だよー
* ↑で"multi-process"となっているが、ワーカーにスレッドも使える(デフォルトはプロセス)
