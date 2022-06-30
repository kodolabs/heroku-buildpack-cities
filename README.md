# heroku-buildpack-cities

Downloads cities JSON data for cities gem
https://github.com/joecorcoran/cities

```bash
heroku buildpacks:add https://github.com/kodolabs/heroku-buildpack-cities.git
```

```ruby
# config/initializers/cities.rb
Cities.data_path = Rails.root.join("tmp/cities")
```
