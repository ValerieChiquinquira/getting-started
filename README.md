# README

## Pre-Getting Started

In order to create this app using Ruby on Rails, you must install and/or verify a suite of stuff.

- To verify if Ruby is installed, you can run the following cmd:

``` ruby -v ```
If it is installed, you'll get a version number. I'm currently running ruby 2.7.0p0. I believe anything about 2..0 will suffice. 

If not, follow these instructions on how to update or otherwise, install ruby. https://www.ruby-lang.org/en/documentation/installation/

- To verify if SQLite3 is installed, run the following cmd:

``` sqlite3 --version ```

If you do not have it installed, read https://www.sqlite.org/download.html for more information. 

This app specifically uses sqlite3 and Rails does recommend for its usage however, it is possible to use MySQL or PostgreSQL for your db.

- To verify if node is installed, 

``` node -v ```

https://nodejs.org/en/download/

- To verify if yarn is installed,

``` yarn -v ```

https://classic.yarnpkg.com/en/docs/install#debian-stable


## Getting Started 

- Clone or download or whatever you'd like, just get it on to your machine in the folder (or if you're a legit adult, the *directory*) you want. 

``` cd directory ```

``` cd blog ```

``` rails server```

- This allow for the app to be seen on your local host, http://127.0.0.1:3000

- Using the local host will allow you to add, edit, delete articles. As well as add, edit, delete comments.

![image](https://user-images.githubusercontent.com/70295448/112772997-12856b00-9002-11eb-8832-ed5345b1d3e5.png)

- To access the console, use the following cmd:

``` rails c ```

- Must exit rails server in order to access the console.
  - can use ctrl + c

## What I've Learned

I've learned that it is best to be dry, incredibly dry, Sahara Desert Dryyy and Rails really lets you be dry. I enjoyed going through this app.

## What's to Come

The plan is to add images and styling. Perhaps with Bootstrap or Tailwinds but honestly, one step at a time. 
