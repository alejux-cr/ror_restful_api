# RoR RESTful API 
 API for book reviews, authentication using the gem devise and Facebook login with koala 

Requirements:
rails '6.0.0'
ruby '2.6.5'
react '16.12.0'

## Important
Go to https://developers.facebook.com, create and app, then create config/initializers/koala.rb file and add:

Koala.configure do |config|

  config.app_id = MY_APP_ID
  config.app_secret = MY_APP_SECRET

end

## Dependencies

## Installation
Install the required gems:
```bash
bundle install
```
Run the migrations:
```bash
rails db:migrate
```
Run the app in localhost:3000:
```bash
rails server or rails s
```
## Tests