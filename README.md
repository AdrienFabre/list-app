# README

## React + Ruby on Rails as API
I used this tutorial: https://medium.com/@bruno_boehm/reactjs-ruby-on-rails-api-heroku-app-2645c93f0814


### Setup Server Side: Ruby on Rails API

In list-app/

#### Install Server Dependencies 

````md

  bundle
```` 

#### Database 

````md

  rake db:drop 
  rake db:create 
  rake db:migrate
  rake db:seed
````

#### Start Server Side

````md

  rails s -p 3001
````

#### Server data at

http://localhost:3001/api/v1/lists

#### Start Server


### Setup Client Side: React

In list-app/client/

#### Install Client Dependencies

````md

  yarn install
```` 

#### Start Client Side

````md

  yarn start
````

#### Website at

http://localhost:3000/