
# Project OnebitExchange

The application converts money by informing from Origin Country to Destination Country.

## Tools

I used the technology RoR (Ruby on Rails) to developer a monolithic system (Pattner MVC).

Follow the used tools:


* Ruby Vesrion 

```
ruby 2.5.1p57 (2018-03-29 revision 63029) [x86_64-linux]
```

* Bundle execute service

```
Bundler version 1.16.6
```

* Rails
```
Rails 5.2.4.2
```

* Version Manager Git and remote Github


* Use manager container with Docker and Docker Compose


## Deploy in local environment 

* Does clone the project in favorite folder and executes the commands.

```
docker-compose build

docker-compose up
```

* Open broswer and digit http://localhost:3000


## Execute intengration and unit test

```
 docker-compose run --rm app bundle exe rspec
 ```
