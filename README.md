# chatroom

# How to run

Install Redis beforehand.

if you are windows system,you should install redis and cmd to 'redis-server redis.windows.conf' and start redis-cli.exe

brew install redis
Clone this repository, and:

bundle install
bundle exec rails db:migrate RAILS_ENV=development
rails server
