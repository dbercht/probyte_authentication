# Probyte Authentication example for Probyte using Rails 4.0.0

Example App using devise. http://github.com/plataformatec/devise

## Installation

Install bundler if you haven't yet:

```
gem install bundler
gem install mysql2
```

Install the gems:

```
bundle install
```

This will install Rails 4.0.0, mysql2 gem and Devise.

Rake devise setup task:

```
rake devise:setup
```

This will:

* drop any existing database
* create a new database
* migrate the database
* create a default user and admin

Run the server and use the credentials provided by the rake task to sign in and test the application.

## License

MIT License. Copyright 2010-2013 Plataforma Tecnologia. http://blog.plataformatec.com.br

