# Node-js Andrew Course

## Node-js

### nodejs - basic package

* [fs](https://nodejs.org/api/fs.html) (file system to create note application)
* [yargs](http://yargs.js.org/docs/) (node user input in terminal or cmd)

### nodejs - server package

* [express](http://expressjs.com/en/api.html) (Use to create node-web-server such as restful-api,webapplication)
* [hbs](http://handlebarsjs.com/) (Handlebar template engine for create view web-application like php,python,ruby)

### nodejs - testing package

* [mocha](https://mochajs.org/) (For use write test-case list)
* [expect](https://github.com/mjackson/expect) (For use Assertion test)
* [supertest](https://github.com/visionmedia/supertest) (For use Assertion test with promise or create restful api test)
* [rewire](https://github.com/jhnns/rewire) (For use spies for coppy function or process fake not sending, use with expect package to create spy)

### nodejs - mongo package

* [mongoose](http://mongoosejs.com/docs/api.html) (Mongodb ORM use to create model,schema and validation)


## Mongodb

### Install
* [install mongodb](https://www.mongodb.com/download-center?jmp=nav#community) 
* unpack and moving in to directory user
* create mongo-data folder
* cd to /bin and use command './mongo --dbpath ~mongo-data'
* run mongo success!


### Tools

* [robomongo](https://robomongo.org/download) (desktop application for gui mongodb structure like phpmyadmin)


## Deploy

### Git-hub

(For Fist-time)
* ssh-keygen -t rsa -b 4096 -C "your_email@example.com"
* cat ~/.ssh/id_rsa.pub

(Use)
* create respo
* git init
* git commit -am 'Initial Commit'
* git remote
* git push origin master


### Heroku

(Setup)
* [install heroku](https://devcenter.heroku.com/articles/heroku-cli#macos) and 
* [create account](https://signup.heroku.com/)
* open terminal use command 'heroku login'
* add ssh to heroku use 'heroku keys:add' and 'ssh -v git@heroku.com'
* setup success!

(Use)
* go to directory
* create heroku use command 'heroku create'
* push heroku to server 'git push heroku'
* view web-page to input 'heroku open'
* success! 


