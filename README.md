# README

This README would normally document whatever steps are necessary to get the
application up and running.

## Dependecies:

* Ruby version  2.2
* AngularJS 1.4
* Angular-nvd3 ?
* System dependencies Tested on MacOS X 10.10.4


## Deploymentation Guide
```bash
 $ bundle install
 ```  
 Copy config/database.yml.example file to config/database.yml and overwrite database connection settings if necessary.
 ```bash
 $ bundle exec rake db:reset
 $ bundle exec rake db:migrate
 ```
To load database with test data:
```bash     
$ bundle exec rake db:populate
$ rails server
```