### With Rails

* こちらもconfigファイルが無いから"rails server"を使わずコマンドから指定する or initializerで値を設定する必要がある

```ruby
# Iodine setup - use conditional setup to allow command-line arguments to override these:
if(defined?(Iodine))
  Iodine.threads = ENV.fetch("RAILS_MAX_THREADS", 5).to_i if Iodine.threads.zero?
  Iodine.workers = ENV.fetch("WEB_CONCURRENCY", 2).to_i if Iodine.workers.zero?
  Iodine::DEFAULT_SETTINGS[:port] = ENV.fetch("PORT") if ENV.fetch("PORT")
end
```

* https://github.com/boazsegev/iodine#running-with-rails
