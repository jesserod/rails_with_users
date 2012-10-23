rails_with_users
================

An example rails app that has user login code from scratch, including reasonable security approaches

Got instructions from:
- http://rubysource.com/rails-userpassword-authentication-from-scratch-part-i/
- http://rubysource.com/rails-userpassword-authentication-from-scratch-part-ii/

Aside from the code edits listed there, here are the commands I ran to make this
sudo gem install sqlite3 bcrypt
rails generate model user
rails g controller users new
rake db:create
rake db:migrate
rails g controller sessions login home profile setting
rm public/index.html
