### WebSocket

* Rack Hijacking APIを使っていない
  * 参考: [File: SPEC — Documentation for rack/rack](https://www.rubydoc.info/github/rack/rack/file/SPEC#label-Hijacking)
  * hijack処理の為に不要な処理が多くなってしまって、結果パフォーマンスも悪くなるから、らしい
  * [\[RubyConf 2018\] High\-Speed Cables for Ruby \- Speaker Deck](https://speakerdeck.com/palkan/rubyconf-2018-high-speed-cables-for-ruby?slide=52)
* [Add WebSocket and SSE options](https://github.com/rack/rack/pull/1272)に準拠している
  * 提案者の一人。もうひとりは[ohler55](https://github.com/ohler55)(ojの作者)
  * 実はohler55もアプリケーションサーバを作っている [ohler55/agoo](https://github.com/ohler55/agoo)
