# Build a CLI Application with External Data

## Overview

- [What to Expect from the Project Review](#expectations)
- [Project Requirements](#requirements)
- [Instructions](#instructions)
- [Practicing for Success on Learn](#success)
- [Resources](#resources)

Congrats! It’s time to work on your first project. In this lesson you're going to build a [Ruby gem](https://guides.rubygems.org/what-is-a-gem/) that provides a Command Line Interface (CLI) to an external data source. The CLI will be composed of an Object Oriented Ruby application. You'll use all you've learned about Ruby and [CLI Applications in Ruby](https://learn.co/tracks/full-stack-web-development-v5/intro-to-ruby-development/command-line-applications/cli-applications-in-ruby) to complete this project.

**Please note that while you will be writing code to [scrape data](https://learn.co/tracks/full-stack-web-development-v5/object-oriented-ruby/scraping/scraping) or utilize an API from a public website, we are really looking for you to demonstrate your ability  to write concise, easy-to-read Object-Oriented Ruby code (e.g. objects, not hashes; separation of concerns). The details of the regex's or the selectors you use to parse your scraped web pages are less important.**

## <a id="expectations">What to expect from the Project Review</a>

Project reviews are focused on preparing you for [technical interviews](https://www.brightnetwork.co.uk/career-path-guides/technology-it-software-development/five-ways-stand-out-your-technology/what-expect-technical-interview/). Treat project reviews as if they were technical interviews, in both attitude and technical presentation.

During your project review, be prepared to:

1. Explain your code from execution point to exit point. You will also be asked questions that test your knowledge of Ruby fundamentals. Use the best technical vocabulary you can. We’ll help you with the words you can’t remember or those you find difficult to pronounce. 20-25 minutes 
2. Refactor code. 10-20 minutes

If any requirements are missing or if significant gaps in understanding are found, be prepared to do one or all of the following:

- Extend the application with a new feature, more data, a different domain etc. 
- Submit an improved version
- Meet again for another Project Review

What won't happen:

- You won't be yelled at, belittled, or scolded
- You won't be put on the spot without support
- There's nothing you can do to instantly fail or blow it

## <a id="requirements">Project Requirements</a>

1. Provide a [CLI](https://github.com/learn-co-curriculum/cli-interfaces-readme#program-loop) 
2. Your [CLI application](https://learn.co/tracks/full-stack-web-development-v5/intro-to-ruby-development/command-line-applications/cli-applications-in-ruby) must provide access to data from a web page.
3. The data provided must go at least one level deep. A "level" is where a user can make a choice and then get detailed information about their choice. Some examples are below:
    - Movies opening soon - Enter your zip code and receive a list of movies and their details.
    - Libraries near you -  Enter your zip code and receive a list of libraries and their details.
    - Programming meetups near you - Choose from an events list and receive details.
    - News reader - List articles and read an article of your choosing.
4. Your CLI application should not be too similiar to the Ruby final projects (Music Library CLI, Tic-Tac-Toe with AI, Student Scraper). Also, please refrain from using [Kickstarter](https://learn.co/tracks/full-stack-web-development-v5/object-oriented-ruby/scraping/kickstarter-scraping-lab) as that was used for the scraping 'code along'. 
5. Use good OO design patterns. You should be creating a collection of objects, not hashes, to store your data. *Pro Tip: Avoid scraping data more than once per web page - utilize objects you have already created. It will speed up your program!*

[World's Best Restaurants](https://github.com/cjbrock/worlds-best-restaurants-cli-gem) was built by a Learn student, is maintained by Flatiron School staff, meets these requirements, and is well coded. Take the time to clone, run, and look through the code in detail - it'll really help.

*If you have time for an extra challenge, [create a gem](https://guides.rubygems.org/make-your-own-gem/) from your application. Want more? Try [publishing your gem to RubyGems.org](https://guides.rubygems.org/publishing/).*


## <a id="instructions">Instructions</a>

1. Watch this [video walkthrough](https://www.youtube.com/watch?v=_lDExWIhYKI) of building a basic CLI Gem called [Daily Deal](https://github.com/learn-co-curriculum/daily_deal) before you begin. Review the [Student Scraper Project](https://learn.co/tracks/full-stack-web-development-v5/object-oriented-ruby/final-projects/student-scraper), which provides a good example of how scraping concerns can be separated into a distinct class.

2. Build your application. This is going to be different from labs you have done on Learn. Do *not* click `Open IDE` and create your application within the lesson files. Instead:
    - [Watch this video on how to create and continue your project in the IDE In Browser](https://www.youtube.com/watch?time_continue=317&v=YZNXWWHUO-E)
    - [Use this IDE Sandbox](https://learn.co/tracks/online-software-engineering-structured/procedural-ruby/command-line-applications/cli-applications-in-ruby).
    *Do not close the Sandbox without completing the next step or your work will be lost.*
    - After your repo is pushed up to Github, make sure you have [a good README.md](https://gist.github.com/PurpleBooth/109311bb0361f32d87a2) with a short description, install instructions, a contributors guide and a link to the license for your code (students usually use the [MIT license](https://opensource.org/licenses/MIT)).
    - To continue working on your project, you'll need to delete extra project files in the Sandbox and clone your project down each time. [This article](http://help.learn.co/workflow-tips/learn-gem/how-to-manually-open-a-lab) includes instructions on how to clone down a repo.
    - Make sure to commit early and commit often. [Commit messages should be meaningful](https://chris.beams.io/posts/git-commit/) (clearly describe what you're doing in the commit) and accurate (there should be nothing in the commit that doesn't match the description in the commit message). Most of your commits should have under 15 lines of code and a 2 line commit is perfectly acceptable. Good rule of thumb is to commit every 3-7 mins of actual coding time.
    - [Use this checklist](https://docs.google.com/forms/d/1ItDHkNbtHJP8T2G28Nqc3Ad8MppbPDpqv9AijAOCFDA/) as you complete your project and submit when you are done.

3. Documentation 
    - While you're working on it, record a 30-minute coding session with your favorite screen capture tool. During the session, either think out loud or not. It's up to you. You don't need to submit the video, but we may ask for it at a later time.

4. Submission 
    - [Submit this checklist](https://docs.google.com/forms/d/1ItDHkNbtHJP8T2G28Nqc3Ad8MppbPDpqv9AijAOCFDA/) after confirming all requirements are met.
    - Prepare a video demo (narration helps!) describing how a user would interact with your working gem. Some common video recording tools used are [Zoom](https://zoom.us/), [Quicktime](https://www.apple.com/quicktime/download/), and [Nimbus](https://chrome.google.com/webstore/detail/nimbus-screenshot-screen/bpconcjcammlapcogcnnelfmaeghhagj?hl=en). After you create your demo, publish it on a service like [YouTube](https://www.youtube.com/) or [Google Drive](https://www.google.com/drive/).
    - Write a blog post about the project and process.
    - On Learn, submit links to the GitHub repository for your app, your video demo (not your 30-minute coding session), and your blog post each to the corresponding textbox in the right rail, and hit "I'm done" to wrap it up.  

## <a id="success">Practicing for Success on Learn</a>

#### Be scrappy.
- If you make a mistake, correct yourself! We all make mistakes, I promise.
- Think on your feet. Feel free to look things up while you're pairing with us. You'll be asked to expand on concepts you implemented and you will be pushed to the edge of your knowledge.
- Explain the details. We're curious!
- Don’t worry if your code isn’t perfect the first time - focus on getting something working, then refactoring to improve it.

#### Make no little plans.
- You're going to learn a ton. We will give pointers and show you ways to improve your code. This isn't telling you that your code is wrong, it's simply us teaching. Whatever you don't quite understand will be explained.
- Be proud of your project and your code, and show confidence in it. 

#### Radiate positivity.
- Present yourself and your project in the best way possible. 
- Be open to feedback, both positive and constructive. 
- Remember, the interviewer is a person too. Be nice to them!

#### Work Together.
- Trust yourself.
- Trust us - our goal is to help you be successful in achieving your goals.
- We understand that this process can be stressful. We’re here to help you through. 

#### Pursue mastery.
- Use the best technical vocabulary you can. We’ll help you with the words you can’t remember, or if you’re unsure about how something is pronounced. 
- Ask questions! Curiosity and willingness to learn are hugely valued in our industry. If you haven’t heard of something, that’s okay - use this opportunity to learn about it!


## <a id="resources">Resources</a>

- [Bundler](https://bundler.io/v1.12/guides/creating_gem.html)
- [Git Repository Basics](https://learn.co/tracks/full-stack-web-development-v5/git-and-github/git/git-repository-basics)
- [Environments, Requiring Files, Bundler, and Gems](https://www.youtube.com/watch?v=XBgZLm-sdl8) 
- [Video- CLI Data Gem Walkthrough](https://www.youtube.com/watch?v=_lDExWIhYKI)
- [Video- CLI Data Gem Walkthrough: Creating a CLI Scraper Gem](https://www.youtube.com/watch?v=Y5X6NRQi0bU)
- [Video- Common Anti-Patterns in CLI Data Gem](https://www.youtube.com/watch?v=cbMa87oWv08)
- [Video- Student Example 1: Refactoring CLI Data Gem](https://www.youtube.com/watch?v=JEL_PXr74qQ)
- [Video- Student Example 2: Refactoring CLI Data Gem](https://www.youtube.com/watch?v=Lt0oyHiKWIw)
- [How to build a ruby gem](http://guides.rubygems.org/make-your-own-gem/)
- [How to publish your gem](http://guides.rubygems.org/publishing/)


<p class='util--hide'>View <a href='https://learn.co/lessons/cli-data-gem-assessment'>CLI Data Gem Project</a> on Learn.co and start learning to code for free.</p>

<p class='util--hide'>View <a href='https://learn.co/lessons/cli-data-gem-assessment'>CLI Data Gem Portfolio Project</a> on Learn.co and start learning to code for free.</p>
