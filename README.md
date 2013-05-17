This is the configuration for ZombiePoet, my personal IRC bot, which idles in
various IRC channels. It is based on [supybot][supybot].

The main configuration lies in `ZombiePoet.template.conf`, all plugins are
contained as Git submodules. After getting this repository, you have to update
the submodules by running `git submodule init && git submodule update`.

The config file contains some variables, which are surrounded by double curly
braces, for example like this:

  supybot.plugins.Services.NickServ.password.ZombiePoet: {{PASSWORD}}

In order to run the bot, you have to substitute the variables with their real
values.

[supybot]: https://github.com/jamessan/supybot
