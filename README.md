Simple use of github action with Rails project

## Info

- Web: Rails 6.0.0
- Database: PostgreSQL
- Testing: Rspec

## Note

```
# initialize Rails app
rails new rails-github-actions-example --skip-turbolinks --skip-spring --database=postgresql -T

# Add rspec gem
gem "rspec-rails", "~> 3.8"

# Add User scaffold
rails generate scaffold User name:string email:string

# run rspec
rspec
```