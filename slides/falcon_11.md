### Multi-FiberとRails

* Multi-FiberベースでRailsはちゃんと動くのか?
  * 実は多少怪しくてですね [Store connection_handler per-fiber and per-thread.](https://github.com/rails/rails/pull/37070)
  * (もうマージ済みだが) [Make ActiveSupport::Logger Fiber-safe](https://github.com/rails/rails/pull/36753) とかの話もある
