Module One Final Project: WordBank App
====================================

## Table of contents
* [General info](#general-info)
* [Technologies](#technologies)
* [Setup](#setup)
* [Examples of Use](#examples-of-use)
* [Credits](#credits)

---

## General info
This project is the capstone project of MOD 1 of the Flatiron School Full Stack Software Engineering program. It is a Ruby CLI dictionary that allows users to: 
- Create an account
- Search for any word from the WORDSAPI
- See the definition of that word and save it to a personal word list
- Retrun the full personal word list with definitions

The user interacts with the app solely through the CLI in a terminal. 

---

## Technologies

This application was written in Ruby. Thus, Ruby is required to be installed on your machine. The application also requires the following [Ruby Gems](https://rubygems.org/) to function:

require 'pry'
require 'rest-client'
require 'uri'
require 'net/http'

require 'json'
- [rest-client](https://rubygems.org/gems/rest-client/versions/1.8.0): to communicate the the WORDSAPI.
- [openssl](https://rubygems.org/gems/openssl): To securely connect to WORDSAPI over SSL. 

Further Ruby Gems were used in the development of the application:

- [pry](https://rubygems.org/gems/pry): To help understand what's going on in the application
- [activerecord](https://rubygems.org/gems/activerecord): For the associations of the classes in the backend
- [sqlite3](https://rubygems.org/gems/sqlite3): To build and manage the database



## Examples of Use

This is what the application looks like when its up and running:


   ![](/images/wordbankdemo.gif)


## Setup

To get the application up and running on your machine, follow these steps:

1. Make sure you have Ruby installed by opening your terminal and typing, 

   ```ruby -v ```

You should get something like this 

   ```ruby 2.6.1p33 (2019-01-30 revision 66950) [x86_64-darwin18] ```
   
If you don't have ruby installed, you'll have to get that up and running in your machine first. You can do that by going to the [Official Ruby Language Downloads](https://www.ruby-lang.org/en/downloads/) page and following the instructions to download and install ruby on your computer. 
   
2. Download this repository

3. Open up your terminal. In your terminal, cd into the repository you just downloaded like so, 

   ``` cd your/path ```
   
   in my computer, that would look like this:
   
   ``` cd /Users/rachfuerst/Documents/flatiron-school/mod-1/final-project/module-one-final-project-guidelines-austin-web-102819 ```

5. run this command: 

   ``` bundle install ```
   
6. Then: 

   ``` ruby bin/run.rb ```

5. Follow the in prompt commands of the app!

## Credits


The humble developers in training that built this are:


**Rachel Fuerst** [LinkedIn](https://www.linkedin.com/in/rachfuerst) // [Github](https://github.com/crayray)

&

**Brittney Haselmayer** [Github](https://github.com/brittneyhaselmayer)