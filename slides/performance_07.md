## Performance

* クライアント数が64になった辺りからFalconが""Errno::EPIPE: Broken pipe"を吐きまくって死亡
  * 色々チューニングしたけど駄目だった
* Puma、iodineは問題無く通った
  * 雑感としては、クライアント数が少ないうちは iodineの方が高速、クライアント数が多くなった場合はPumaの方がはやかった
  * Pumaはクライアント数に影響なく結果が安定していた
