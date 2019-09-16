### With Rails

* Rackのhandelrが提供されているので、gemを追加し、"rails server -u falcon"でいける
* が、Pumaのようなconfigファイルは無く引数でオプションは指定する必要がある、かつ、rails server経由ではオプションが指定出来ないので、falconで提供されているコマンドを使うのが良さそう
* Rack handler経由の起動だとasync-containerが使われないように見えるので、そういう意味でもfalconのコマンド経由が望ましいか
