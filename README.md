# Welcome to my user management app

## prerequisition
``` shell
$ bundle install
$ rake db:migrate

# create the faker testing users
$ bundle exec rake db:reset
$ bundle exec rake db:populate
$ bundle exec rake db:test:prepare
```