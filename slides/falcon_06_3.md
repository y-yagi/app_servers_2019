### asyncシリーズ

* 古来よりRubyでReactorといえば[eventmachine/eventmachine](https://github.com/eventmachine/eventmachine)
  * [macournoyer/thin](https://github.com/macournoyer/thin)もEventMachineを使っていた
  * しかしEventMachineは色々問題があった
  * 作者も色々と踏んだ( https://github.com/socketry/rubydns/issues/45 https://github.com/socketry/rubydns/issues/14 )らしい
* その後、[celluloid/celluloid](https://github.com/celluloid/celluloid)も使っりしていたが、バグやデザインissueにより色々と苦労したらしい
  * [Remove deprecated](https://github.com/celluloid/celluloid/pull/710)
* そんな背景もあって作者が自作したとのこと
