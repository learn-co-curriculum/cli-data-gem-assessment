# Build a CLI Application with External Data

## Overview

In this lesson you're going to build an application that provides a Command Line Interface (CLI) to an external data source. The CLI will be composed of an Object Oriented Ruby application. 

**Please note that while you will be writing code to scrape data from a public website, what we're really looking for is your capacity to effectively write good object oriented ruby code (objects, not hashes, separation of concerns, etc.) - we're less interested in the details of the regex's or selector you're using to parse the web pages that you're scraping.**

## Requirements

1. Provide a CLI
2. CLI must provide access to data from a web page.
3. The data provided must go at least one level deep, generally by showing the user a list of available data and then being able to drill down into a specific item.
4. The CLI application can not be a Music CLI application as that is too similiar to the other OO Ruby final project. Also please refrain from using Kickstarter as that was used for the scraping 'code along'. Look at the example domains below for inspiration.
5. Use good OO design patterns. You should be creating a collection of objects - not hashes.


*For bonus points, instead of just creating an application, create a gem and for extra bonus points try publishing it to RubyGems.*

### Example Domains

- Movies opening soon - Enter your zip code and receive a list of movies and their details.
- Libraries near you -  Enter your zip code and receive a list of libraries and their details.
- Programming meetups near you, list details.
- News reader - List articles, read article.

[now-playing](https://github.com/learn-co-curriculum/now-playing-cli-gem) is an example of a gem that would meet these requirements.
[worlds best restaurants](https://github.com/cjbrock/worlds-best-restaurants-cli-gem) was built by a Learn student, maintained by Flatiron School staff, meets these requirements, and is well coded.
Take the time to clone, run and look through the code for both of these in detail - it'll really help.

## Instructions

1. Watch this [video walkthrough](https://www.youtube.com/watch?v=_lDExWIhYKI) of building a CLI Gem called [Daily Deal](https://github.com/learn-co-curriculum/daily_deal) before you begin.
2. Create a new repository on GitHub for your application, ie: `name-cli-app`.
3. When you create the CLI app for your assessment, add the spec.md file from this repo to the root directory of the project, commit it to Git and push it up to GitHub.
4. Build your application. Make sure to commit early and commit often. Commit messages should be meaningful (clearly describe what you're doing in the commit) and accurate (there should be nothing in the commit that doesn't match the description in the commit message). Good rule of thumb is to commit every 3-7 mins of actual coding time. Most of your commits should have under 15 lines of code and a 2 line commit is perfectly acceptable. **This is important and you'll be graded on this**.
5. Make sure to create a good README.md with a short description, install instructions, a contributors guide and a link to the license for your code.
6. While you're working on it, record a 30 min coding session with your favorite screen capture tool. During the session, either think out loud or not. It's up to you. You don't need to submit the video, but we may ask for it at a later time.
7. Make sure to check each box in your spec.md (replace the space between the square braces with an x) and explain next to each one how you've met the requirement *before* you submit your project.
8. [Fill out this checklist.](https://docs.google.com/forms/d/1ItDHkNbtHJP8T2G28Nqc3Ad8MppbPDpqv9AijAOCFDA/)
9. Prepare a video demo (narration helps!) describing how a user would interact with your working gem.
10. Write a blog post about the project and process.
11. On Learn, submit links to the GitHub repository for your app, your video demo, and your blog post each to the corresponding textbox in the right rail, and hit "I'm done" to wrap it up.  


## If you're a Learn-Verified Premium student: 

Unlike the rest of the curriculum, if you have any questions about your assessment or need help with it, please don’t use the Ask New Question feature. Rather than working with Learn Experts, please reach out to your Learn Instructor responsible for this section instead.

Watch for an email from Learn with instructions to schedule an assessment. If you don't receive the email within a day or so after submission, get in touch!

### Be Prepared to:

1. Explain your code from execution point to exit point. We're making sure you wrote it and understand how it works, nothing else. 10-20 minutes
2. Refactor code. 10-20 minutes

If necessary, after the assessment, be prepared to:

1. Extend the application with a new feature, more data, a different domain etc. 20-30 minutes
2. Submit an improved version.

### What to expect from the assessment

Project reviews are focused on preparing you for technical interviews. Treat project reviews as if they were technical interviews, in both attitude and technical presentation. 

#### Be scrappy.
- If you make a mistake, correct yourself! We all make mistakes, I promise.
- Think on your feet. Feel free to look things up while you're pairing with us. You'll be asked to expand on concepts you implemented and you will be pushed to the edge of your knowledge.
- Explain the details. We're curious!
- Don’t worry if your code isn’t perfect the first time - focus on getting something working, then refactoring to improve it

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


### What won't happen:

- You won't be told you're ever wrong.
- You won't be yelled at, belittled, or scolded.
- You won't be put on the spot without support.
- There's nothing you can do to instantly fail or blow it.

## Resources

- [How to build a ruby gem](http://guides.rubygems.org/make-your-own-gem/)
- [How to publish your gem](http://guides.rubygems.org/publishing/)
- [Environments, Requiring Files, Bundler, and Gems](https://www.youtube.com/watch?v=XBgZLm-sdl8) 
- [Video- CLI Data Gem Walkthrough](https://www.youtube.com/watch?v=_lDExWIhYKI)
- [Video- CLI Data Gem Walkthrough: Creating a CLI Scraper Gem](https://www.youtube.com/watch?v=Y5X6NRQi0bU)
- [Video- Common Anti-Patterns in CLI Data Gem](https://www.youtube.com/watch?v=cbMa87oWv08)
- [Video- Student Example 1: Refactoring CLI Data Gem](https://www.youtube.com/watch?v=JEL_PXr74qQ)
- [Video- Student Example 2: Refactoring CLI Data Gem](https://www.youtube.com/watch?v=Lt0oyHiKWIw)


<p class='util--hide'>View <a href='https://learn.co/lessons/cli-data-gem-assessment'>CLI Data Gem Project</a> on Learn.co and start learning to code for free.</p>
