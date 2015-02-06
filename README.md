#Active Record Chess Game
A chess game using ActiveRecord and Sinatra written over three days by four folks
as an exercise for Epicodus programming school.

##Setup Instructions:

Gems Used:

sinatra
sinatra-contrib
sinatra-activerecord
rake
pg
pry
rspec
shoulda-matchers
Install Bundler:
```
$ gem install bundler
```
Run Bundler:
```
$ bundle
```
Start the database:
```
$ postgres
```
Create databases:
```
$ rake db:create
$ rake db:migrate
$ rake db:test:prepare
```
Run the Sinatra application:
```
$ ruby app.rb
```
Navigate to `localhost:4567` witha browser and enjoy!

Authors

Jackie Fletcher, Alex Kaufman, Benjamin Herson, and Gabe Finch

MIT License
