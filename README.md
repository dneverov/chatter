# Chatter

An example from [Build a Twitter clone in 10 minutes with Rails, CableReady, and StimulusReflex](https://youtu.be/F5hA79vKE_E)

Things you may want to cover:

* Ruby version

Ruby 2.6.5  
Rails 6.0.3.1

* System dependencies

* Configuration

(FYI)

      rails new --skip-spring --webpack=stimulus chatter
      cd chatter
      bundle add redis cable_ready stimulus_reflex
      yarn add cable_ready stimulus_reflex
      bundle exec rails stimulus_reflex:install

      bundle exec rails g scaffold Post username body likes_count:integer reposts_count:integer --no-jbuilder

* How to run the test suite

* Services (job queues, cache servers, search engines, etc.)

* Deployment instructions

* ...
