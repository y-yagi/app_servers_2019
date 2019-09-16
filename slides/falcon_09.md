### Falcon

* 普通にアプリケーションサーバ
  * HTTP/2やEarly Hintsのサポートもちゃんとある
* Virtual HostのようなHTTPサーバ相当の機能も一部提供している(まだexperimental)
  * https://github.com/socketry/falcon#virtual-hosts
  * SNI-based proxy
    * 参考: [注目の集まるSNI（Server Name Indication）導入の必要性とは | グローバルサインブログ](https://jp.globalsign.com/blog/articles/server_name_indication.html)
