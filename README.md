# README

* Ruby version: ruby 2.6.3p62 
* Rails version: Rails 6.1.3

<h2>How to run this project?</h2>
1. Check if you have rbenv, node, yarn, bundler, ruby, rails installed on your local machine using the following commands 

```
rbenv --version 
node --version
yarn --version
bundler --version
ruby --version
rails --version
```

2. Install rbenv, node, yarn, bundler, ruby, rails on your local machine. 

```
brew install rbenv
brew install node
brew install npm
brew install yarn
brew install rails
brew install bundler
brew install ruby
```

3. Install the webpacker using the following command.

```
bundle exec rake webpacker:install
```

4. Now use the following commands to set up the database

```
bundle e rails db:setup
bundle e rails db:migrate
```

5. Now run the project using the following command 

```
rails s
OR 
bundle execute rails s
```
