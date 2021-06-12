# Google Auth 2.0, device demo app by Ruby on Rails 6.*
## Version
- Ruby 2.7.1  
- Rails 6.0.3.7  
## Step
1. Clone this repository
2. Take commands in this order
```
$ source env.sh
$ build
$ rails db:create
$ cp .env.sample .env # このタイミングで Google Auth 2.0 の クライアントIDとクライアントシークレットを.envに記述
$ up
```
5. You can access http://localhost:3000 
## Options
```
$ source env.sh
$ rspec
$ rubocop
$ yarn
```
## Precautions
User using Docker for Windows need to take this command.
```
$ git config --global core.autocrlf input
```
