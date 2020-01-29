#React Rails TODO リスト

<h1 align="center">
  <img src="https://github.com/aizwellenstan/fivexruby-todo/blob/master/screenshot.png?raw=true" alt="screenshot" width="600px"/>
</h1>

##Features
- Register/Login
- User can Create/Delete their own task
- Task
1. title
2. body
3. start_time
4. end_time
5. level

- sort task by 
1. time_end
2. time_start
3. level

- suprate task
1. onhand
2. passive
3. ative

- filter task by title || body 

# Contributing
## Install rails
1. `sudo apt-get install curl`
2. `command curl -sSL https://rvm.io/pkuczynski.asc | gpg --import -`
3. `\curl -sSL https://get.rvm.io | bash -s stable --rails`
4. `sudo apt install postgresql-contrib libpq-dev`
5. `sudo apt install git`
6. `git clone https://github.com/aizwellenstan/fivexruby-todo`
7. `cd server`
8. `sudo apt install rbenv`
9. `sudo rbenv exec gem install bundler`
10. `rbenv rehash`
11. `source ~/.rvm/scripts/rvm`
12. `rvm install ruby 2.6.3`
13. `rvm --default use 2.6.3`
14. `gem install bundler:2.0.2`
15. `bundle`
16. `rails db:setup db:migrate db:seed`
17. `rails s`