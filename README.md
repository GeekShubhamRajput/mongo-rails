# Rails + Mongo Demo

This repo contains the demo of Mongo.

Required things to setup this application :

* Ruby version :- ruby '2.7.0' and rails 6.1.7

Steps to build from scratch this :-  

1. Create new rails application 
`rails new app_name`

2. Add gem mongoid in your gemfile

3. Create User model
`rails g model User name email`

4. Add mongo config
`rails g mongoid:config`

5. Create users controller and index action
`rails g users index`

6. Update root path as users index
  