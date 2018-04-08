# surveyor

Surveyor is a simple survey app created with React, Redux, Ruby on Rails, and PostgreSQL. Log in as an admin to create questions and send people the specified link to get answers.

### Installation

To install the rails packages, first check your Ruby version, `ruby -v` and then check your gem version, `gem --version`. If you don't get an error, then ruby is installed. cd into `survey_app`. You will be able to install the rails packages by using `bundle` in the terminal or command line script. Please make sure you check your rails version by using `rails -v`. Run the rails server by using `bundle exec puma -C config/puma.rb -b tcp://127.0.0.1:3001` because postgresql is listening on port 3000.

### Current Versions

- Rails version: 5.1.6
- Ruby version: 2.4.1 (x86_64-darwin17)
