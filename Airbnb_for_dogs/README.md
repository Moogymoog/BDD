# Airbnb_For_Dogs



>Created on 24/10/2019 by Alexandre Moog



**Note aux correcteurs**

My program is complete.

To test the program please run :
bundle install
rails db:migrate
rails db:seed
rails c


## Content



- **db/seed** : Test and explaination
- **db/migrate**: All the migrations
- **app/models** : All the models
- **Gemfile, Gemfile.lock** : Gem and dependencies. See below.



## Classes



Provides methods and variables to organize class process and its different phases.



- # ApplicationRecord
- # City
- # Dog
- # Comment
- # Dogsitter
- # Stroll



## Gemfile



```



source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '2.5.1'

gem 'faker'
gem 'table_print'


gem 'rails', '~> 5.2.3'

gem 'sqlite3'


gem 'uglifier', '>= 1.3.0'


