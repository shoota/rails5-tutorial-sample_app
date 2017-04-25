# README

This README would normally document whatever steps are necessary to get the
application up and running.

Things you may want to cover:

* Ruby version

```
ruby 2.4.1p111 (2017-03-22 revision 58053) [x86_64-darwin15]
```

* Configuration

```
$ bundle update
$ bundle install --without production
```

* Database creation

on development
```
$ rails db:migrate
```

on production
```
$  heroku run rails db:migrate
```

* Database initialization

* How to run the test suite

```
$ rails test
```
