# Rails Templates

Quickly generate a rails app with the default configuration
using [Rails Templates].


## Minimal

Get a minimal rails app ready to be deployed on Heroku with Bootstrap, Simple form and debugging gems.

```bash
rails new \
  --database postgresql \
  -m https://raw.githubusercontent.com/AlxFrst/Rails-Template/master/minimal.rb \
  CHANGE_THIS_TO_YOUR_RAILS_APP_NAME
```

## Devise

Same as minimal **plus** a Devise install with a generated `User` model.

```bash
rails new \
  --database postgresql \
  -m https://raw.githubusercontent.com/AlxFrst/Rails-Template/master/devise.rb \
  CHANGE_THIS_TO_YOUR_RAILS_APP_NAME
```
