# README
My first attempt with rails scaffold. 
So far rails have been really nice to work with. :)

`git clone https://github.com/jradd/sample-app.git`


## Initialize rails environment.
For now, I just run `rails new .` and say `no` to all the prompts. 
For some reason 'signup' doesn't route to 'create-new-user.' so fix that.

```
cd sample-app
bundle install --without production
rails db:migrate
rails server -b 0.0.0.0 -p 3200
```  


* Ruby version  
3.9.1
* System dependencies  


password_digest working with 'bcrypt 3.1.7' 

* Configuration

* Database creation  
working with sqlite

* Database initialization

* How to run the test suite  

`rails test models:user`

still working on tests.

