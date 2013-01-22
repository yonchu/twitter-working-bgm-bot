Python twitter bot for @melty\_blood\_bot
====================

Bot account: [@working_bgm_bot](https://twitter.com/working_bgm_bot)

Installation
---------------------

Clone from http://github.com/yonchu/twitter-working-bgm-bot
and install it with::

```console
$ git clone git://github.com/yonchu/twitter-working-bgm-bot.git
$ git submodule update --init
$ git submodule foreach "git checkout master"
```

Usage
---------------------

Create your ``bot.cfg`` file.

```console
$ cd config
$ cp bot.cfg.sample bot.cfg
```

Edit ``bot.cfg`` to suite your environments.

Initialize.

```console
$ ./working_bgm_bot.py init
```

Run ``working_bgm_bot.py`` using run-script in cron.

```
run-script/run-script start ./working_bgm_bot.py
```
