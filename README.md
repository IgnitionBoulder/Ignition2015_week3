# Ignition 2015 Week 3: Intro to Rails
### Required
#### Ponder and answer these questions as you work through the other material for this week.
- What is a framework?
An abstraction that provides application-specific software that can be selectively changed by users.
- What's the difference between a programming language and a framework?
A programming language is the bones of a framework. It makes up applications, libraries, etc...  A framework is like a library in that it cuts a large deal of coding out of your work and sets the stage for doing lots of ...things?... quicker and easier.  That seems to make sense right?
- What’s the difference between a library and a framework?
A library is a group of functions and objects that serve a specific purpose while a framework is a collection of libraries that have more broad uses generally made for applications
- What languages have frameworks?
Well i'm just throwing it out there but I'm pretty sure you can make a framework for pretty much any language.  I dunno, maybe I'm just throwing this out my ass right now.

#### Resources
- Read [“what is a framework” description](http://www.google.com/url?q=http%3A%2F%2Fwww.theodinproject.com%2Fweb-development-101%2Fintroduction-to-frameworks&sa=D&sntz=1&usg=AFQjCNHVhJ11ysP5eoUpwh7t-A7kzNPjrg) on the Odin project.
- Read the [What is Ruby on Rails](http://www.google.com/url?q=http%3A%2F%2Frailsapps.github.io%2Fwhat-is-ruby-rails.html&sa=D&sntz=1&usg=AFQjCNFN998pBASQXWFuYiDiXn5zYlGJJg)
- Do the [CodeLearn course](http://www.google.com/url?q=http%3A%2F%2Fwww.codelearn.org%2Fruby-on-rails-tutorial&sa=D&sntz=1&usg=AFQjCNGqp-Pl4Qk3anl1eTwqiFKPRJWTjg), Module 1

#### Weekly Project - As a Group
- As a group, create a new Cloud9 project to walk through the [Jumpstart Labs Blogger tutorial](http://tutorials.jumpstartlab.com/projects/blogger.html) sections I0-I4 and push a completed solution up to the repo.
  - In this project, you need use a Cloud9 “Custom” workspace (“Custom” and not “Rails” because you will be setting up your own Rails app inside the Custom workspace).
  - Set up the the workspace such that you create the `blogger` rails folder within your project, but that you only commit the `blogger` folder to GitHub.  This means you will need to run `git init` within `blogger` and do all your commits from there.
  - Starting the app up is going to be different than what Jumpstart Labs tells you.  You are going to run `rails s -p $PORT -b $IP` in the Cloud9 terminal and then visit the link it tells you in the pop up.
  - Each individual needs to put a link to this repo in their deliverables/README.md.
- Once you get your app working on your Cloud9 workspace (or at the very end), deploy it to Heroku (here’s [how](http://installfest.railsbridge.org/installfest/deploy_a_rails_app), and here’s some [additional help](http://www.theodinproject.com/ruby-on-rails/deployment).
  - Stuck? Here’s some [common problems](https://gist.github.com/burtlo/4970471) people run into during the Jumpstart tutorial
  - Include a link to your app on heroku in your deliverables/README.md
- If you’d like to take it to the next level, do section I5 with authentication, and even I6 if you are feeling extra crazy.

#### Pull Request - Instructions
- Follow these steps to submit your Pull Request once you've completed your work
  - Go to your Week3 Repo on GitHub
  - Click on the [Pull Request] button
  - Give your pull request a name: <Your Name> | Week 3 | Deliverables
  - Click "submit"

### Optional
- Complete the [Rails for Zombies](http://railsforzombies.org/) challenges
- Watch [Hartl’s 10 min youtube video about Rails](https://www.youtube.com/watch?v=b_DJdmvBStE).
- Read this Medium [How I learned Ruby on Rails](https://medium.com/how-i-learned-ruby-rails/e08c94e2a51e) article
