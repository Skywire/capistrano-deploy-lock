# Deploy Lock

- Gem for capistrano to lock deployments so others don't deploy over you

## Add to your project:

Add the following to your project Gemfile

~~~
gem 'capistrano-deploy-lock', :git => 'git@github.com:Skywire/capistrano-deploy-lock.git', :branch => 'master'
~~~

Then run 

~~~
bundle install
~~~

Add the following to your project Capfile

~~~
require "capistrano/deploy-lock"
~~~