# Intro to Sinatra / MVC

## Welcome to Module 2!

## Today's Problem:
- We are stuck in the command line!
- (We want to build web applications!)

## We have started to solve our problem:
- Learning about the Request-Response Cycle
  - ...
- Learning about the HTTP protocol
  - ...
- Learning about Rack
  - what is it?
  - what is "localhost"
  - what is a port?
  - how does this tie into RR Cycle?

## Introducing ... REST:
- What is it?
- how does this tie into RR Cycle?
- How does CRUD fit into REST?

## Introducing ... Sinatra:
1. Is a Gem
  - uses ActiveRecord!
  - uses Rack!
2. Why Sinatra?
  - small gem that makes it easy to get started with Ruby web development
  - onramp to Ruby on Rails b/c it's 'Rack-based'
  - onramp to Ruby on Rails b/c it employs 'MVC'

## MVC is...
  - a design philosophy
  - an architectural pattern
  - widespread!
  - separation of concerns for logic of our web application
  - *Interactively get at M / V / C*

## MVC + CRUD + REST
- MVC apps usually adhere to REST for CRUD functionality
- REST_route = action + path

## Today's codebase brought to you by ...
- convention > configuration
- ERB
- macros
- rake tasks
- routing table
- block -> "handler for the route"

## PSA: regarding the tests in this module's labs
- tests try to interact with your web application's interface
- tests therefore require you to build very specifically to their assumptions
- Call us over!

## Deliverables

- View  a homepage
- View a listing of all books
- View a detail page for an individual book
*...*
- Create a new book
- Edit an existing book
- Delete an existing book
