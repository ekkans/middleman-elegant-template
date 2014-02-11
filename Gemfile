# If you have OpenSSL installed, we recommend updating
# the following line to use "https"
source "http://rubygems.org"

gem "middleman", "~> 3.2.0"
gem "slim", "~> 2.0.0"

gem "middleman-gh-pages", "~> 0.0.2"
gem "middleman-livereload", "~> 3.1.0"
# https://github.com/igrigorik/em-websocket/issues/102
gem "em-websocket", git: "https://github.com/igrigorik/em-websocket"

require 'rbconfig'
gem 'wdm', '>= 0.1.0' if RbConfig::CONFIG['target_os'] =~ /mswin|mingw/i
