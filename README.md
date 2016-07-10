## System requirements

1. Ruby 2.1.2

## How to install

From your console, navigate into the main project's directory:

```bash
  $ cd todo-list-api
```
Install gem dependencies:

```bash
  $ bundle install
```

Prepare the database (sqlite3)

```bash
  $ bundle exec rake db:migrate
```

Launch your app

```bash
  $ bundle exec rails s
```

Test your app

```bash
  $ open 'http://localhost:3000/api/v1/test/echo?message=hello'
```


## Some external references

* https://github.com/ruby-grape/grape
* https://github.com/ruby-grape/grape-entity
