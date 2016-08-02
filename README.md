
## Vertalab Playbook

Engineering ideas. Step-by-step guide.


### PROJECT


#### Feasibility study (AM)

*   Case analysis (TL + AM)
*   Rough estimate (minimal value threshold) (TL + AM)


#### Startup Prep Package (AM)

*   Define team roles (AM)
*   Create shared Google Drive project folder and invite members (AM)
*   User stories preparation (BA)
*   Glossary - list of models and their relations (BA + LE)
*   User stories preparation (BA)
*   Define and draw business processes (BA+LE+CEs+TL)
*   Critique of business processes (BA+LE+TL+AM+DE)
*   Diagrams of pages and their relations (BA + DE + LE)
*   Wireframes (DE)
*   Critique of Wireframes (TL+AM+BA+LE+DE)
*   Cost and time estimation for the project + possible risks description (LE) (TL+AM)


* * *


#### Preparations (PM)

*   Define team roles (TL)
*   Approving development process with customers according to Playbook (PM)
*   Project Brief (PM)
*   Set PM tools: (COO)
    *   create Trello board
    *   create project to VertaPult
    *   Linking VertaPult project and Trello board
    *   create Slack group
*   Translate Startup Prep package into Trello tasks
*   Repo creation (TL)
    *   Web hooks
    *   Invite team
*   Initialize the project (LE)
*   Create [Readme file](#readme) (LE)
*   Third party sandbox credentials: request from client or dedicated ours (PM)


* * *


#### Feature development (PM)

##### Pre-coding analysis of the new feature (PM+LE+TL+DE)

*   Understand the client goal (PM)
*   Getting User stories ready (PM)
*   Define the solution (PM+DT+CEs)
*   Review the solution (TL)
*   Wireframes/design (DE+PM)
*   Cost and time estimation for the feature + possible risks description (LE)
*   Translate approved solution into Trello card (PM)



* * *



##### Coding

*   Take ticket with the highest priority on Trello and move from “Next up” to “in progress” List
*   Read Acceptance criteria and view all attached documents to clarify what is needed, if something is not clear ask your PM
*   Create new feature branch - `yi/cool-feature` - [our git workflow](#gitflow)
*   Write code that solves the problem - [our code style guide](#styleguide)
*   Add tests to to be sure code is correct - [our testing guide](#testingguide)
*   Check if your solution meets Acceptance criteria of the task
*   Create Pull Request and create pull request review as a separate card on the Code Review board here [here](https://trello.com/b/BofqDnF4/code-review)
*   Move ticket to the Code review list
*   Ask someone to [review](#code_review) your pull request
*   Work on your pull request based on feedback from your colleagues/Fix PR issues
*   Once approved, merge feature branch into target branch
*   Move Trello ticket to the QA list


###### refs<sup><small>*</small></sup>:

[https://medium.com/@kiosan/how-to-write-code-guide-for-engineers-7bb32bf365f7#.5ptvu2dxq](https://medium.com/@kiosan/how-to-write-code-guide-for-engineers-7bb32bf365f7#.5ptvu2dxq)

* * *


##### Manual Testing (QA)

*   Take Trello ticket from the QA list
*   Check whether deployed solution meets acceptance criteria, if no - move it to the “In progress” list with comments
*   Check if there are no bugs, if there are some - move it to the “In progress” list with comments
*   Move ticket to “Ready for demo” list



* * *



##### Demonstration and approving feature by customer (PM)

*   On the regular demo meeting with client present the recently completed features and fixed bugs (tickets in the “Ready for review” list)
*   Gather client feedbacks
*   Move reviewed tickets to “approved” or “in progress” list depend on the client feedback
*   Make changes in the Project Documentation if needed (PM+LE)



* * *


##### Retrospective and process improvements (COO)

*   Retrospective meetings with the team after each release (PM+COO)
*   Regular customer feedback gathering on Demo and regular calls (PM)
*   Final retrospective meeting once product is live, lessons learned (PM, COO)
*   Process improvements, Playbook renovation if needed, spread lessons learned among the teams, discussing, learning (COO)


* * *


#### Roles* :

*   TL - Tech lead
*   AM - Account manager (sales)
*   COO - Chief Operational Officer
*   PM - Project manager
*   BA - Business analyst
*   DT - development team:
    *   LE - Lead Engineer (person who will lead development on the project)
    *   E - Engineer
*   CE - Consultant Engineer (might be working on a different project, necessary for a fresh pair of eyes and critical perspective)
*   DE - Designer

* One person could play more than one role during the project life cycle. For example: AM may act also as a BA, or PM could be a QA simultaneously etc. Such occasions must be clearly defined in the Project Brief.



* * *



#### Documentation

*   We use Google Drive to store all project related data
*   Our customer has access to the project folder to be on the same page with us
*   Each Project folder must have at least next files/folders:
    *   Documentation: approved user stories, Glossary, Business processes drawing, Diagrams of pages and their relations, Tech Docs
    *   Wireframes
    *   Designs
    *   Resources and credentials
    *   Project Brief
    *   Working files (for docs in progress, unapproved stuff etc.)
*   We attach related documents to trello cards to quickly find all necessary information



* * *



#### Project Brief

This document is created for each project by PM and reviewed by COO and contains:

*   Project name and goal
*   Estimation and deadlines (if exist)
*   Team roles and responsibilities
*   Links to documentation files (user stories, wireframes, Glossary etc.)
*   Release plan (periodicity)
*   Communication plan (meetings periodicity, communication channels, link to the trello board, Slack group name etc)
*   Useful links (staging, production, services)



* * *


#### COMMUNICATION

##### Internal Meetings:

*   Grooming meeting:
    *   Purpose: PM + DT discuss, find solution, estimate tickets in Backlog list. CE or TL must be invited when new feature is discussed
    *   When: before each planning meeting with clients
*   Stand up meeting (if there more than 1 engineer on the project):
    *   Purpose: PM + DT. Each team member summarizes what he did the previous day, what he will do today, and what impediments he faces
    *   When: Daily
*   Retrospective meeting:
    *   Purpose: PM+DT+COO discuss the results of the last release in order to fix impediments team faced and find ways to improve development process
    *   When: after each demo meeting with clients
*   Final Retrospective meeting:
    *   Purpose: PM+DT+COO+AM+TL discuss the results of the project, best practices was used, look for areas required improvements and scope them to the lessons learned
    *   When: once project is finished

##### Meeting with clients:

*   Planning meeting:
    *   What: PM+LE Discuss with the client plan for next release
    *   When before each release.
*   Demo meeting:
    *   What: PM+LE Present and discuss results of current release with the client
    *   When: after each release

##### Communication channels:

*   Emails - official communication
*   UberConference (Skype, Google Hangouts, Slack) - meeting with clients
*   Slack - project team communication
*   Trello — for progress/issue tracking
*   Vertapult - timetracking


* * *


#### Trello workflow

*   Use Trello as a ticket management system for Your project
*   Project Trello Board should have at least 7 columns/stages:
    *   Backlog - list of all open tickets, estimated or not. Every board member may added ticket to this list. On the grooming meeting team investigates the issue described and finds out the solution and estimates.
    *   Next up - list of tasks which must be done in the current release. This list must contain only estimated cards
    *   In progress - list tasks which is currently in work
    *   Code review - list of tasks on the code review
    *   QA - list of tasks which passed Code review and need QA
    *   Approved - Approved tasks by customer which are ready to be included to the upcoming release
*   Trello card requirements (if a card doesn’t meet them it can’t be moved further that Backlog list):
    *   Feature card - must contain Acceptance criterias (checklist) approved by customer
    *   Bug card - must contain clearly described current and expected state of the issue
    *   Design card - must contain related user stories, wireframes, schemas etc.
    *   Investigation card - must contain clear goal and requirements
*   Attach to the ticket all related docs and screenshots which might be helpful
*   People assign themselves to tickets. When in doubt, do not assign a ticket to someone.
*   When assigned to new feature ticket, [create a branch for it](#gitflow) and mention this branch in ticket description
*   Use Trello bot to have clear view on deployments - Roman to describe.


* * *

### DEVELOPMENT


#### STARTING PROJECT



#### README file.

It should include:

*   brief explanation of the project
*   database design and architecture
*   local development setup/description how to run it
*   seed data for local development
*   configuration using environment variables
*   etc...

Every week reread README to check if it up-to-date. Add information to README as soon as you feel it will be useful for rest of the team.

###### refs<sup><small>*</small></sup>:

Good example of [README](https://github.com/Vertalab/guides/blob/master/readme-example.md) to follow. 
[http://tom.preston-werner.com/2010/08/23/readme-driven-development.html](http://tom.preston-werner.com/2010/08/23/readme-driven-development.html) 
[https://robots.thoughtbot.com/how-to-write-a-great-readme](https://robots.thoughtbot.com/how-to-write-a-great-readme)

* * *

#### Server setup

https://github.com/Vertalab/rails-react-es6-ansible-capistrano

#### Include our default Ruby GEMs set.

Default gems:

*   `gem 'haml'` - templating engine for HTML
*   `gem 'coffee-rails'` - CoffeeScript adapter for the Rails
*   `gem 'sass-rails'` - integration with Sass
*   `gem 'dotenv-rails'` - load environment variables from .env file

Monitoring/Debug:

*   `PRY`
*   `God`

Testing:

*   `Rspec`
*   `Capybara`
*   `gem 'shoulda-matchers'`
*   `gem 'simplecov'`
*   `gem 'factory_girl_rails'`
*   `gem 'faker'`

Code quality:

*   `gem 'rubocop'`
*   `haml-lint`
*   `gem 'bullet'`


###### refs<sup><small>*</small></sup>:

[https://docs.google.com/a/vertaline.com/document/d/1O_XEDhMz3PmAbCJGNcOA-N9Mm-uq8XL60hbEwgKYubo/edit?usp=sharing](https://docs.google.com/a/vertaline.com/document/d/1O_XEDhMz3PmAbCJGNcOA-N9Mm-uq8XL60hbEwgKYubo/edit?usp=sharing)

* * *


#### Set envairment variables using `.env` file:

###### refs*:

[http://12factor.net/config](http://12factor.net/config) 
[https://devcenter.heroku.com/articles/config-vars](https://devcenter.heroku.com/articles/config-vars)



* * *


#### GIT WORKFLOW

*   Keep the master branch deployable at all time
*   Write informative commit messages
*   Feature GIT workflow:

*   checkout from master `git checkout -b yi/your_feature_branch` where `yi` is your initials
*   commit/push often
*   `git fetch`
*   `git checkout master`
*   `git pull`
*   `git checkout yi/your_feature_branch`
*   `git rebase origin/master`
*   fix conflicts
*   `git push origin vh/your_feature_branch`
*   create Pull Request
*   repeat

###### refs<sup><small>*</small></sup>:

[http://reinh.com/blog/2009/03/02/a-git-workflow-for-agile-teams.html](http://reinh.com/blog/2009/03/02/a-git-workflow-for-agile-teams.html)  
[https://github.com/thoughtbot/guides/tree/master/protocol/git](https://github.com/thoughtbot/guides/tree/master/protocol/git) 
[https://ariejan.net/2011/07/05/git-squash-your-latests-commits-into-one/](https://ariejan.net/2011/07/05/git-squash-your-latests-commits-into-one/)



* * *


#### STYLE

*   Use propper naming and formatting - [guide](https://github.com/thoughtbot/guides/tree/master/style)
*   Ruby StyleGuide - [guide](https://github.com/bbatsov/ruby-style-guide)
*   Rails StyleGuide - [guide](https://github.com/bbatsov/rails-style-guide)
*   PS: most Ruby/Rails recommendations are covered with awesome gem called `rubocop`. Just install it, run from time to time and fix code where needed.


* * *


#### TESTING / QUALITY

*   We use Rspec/Capybara for testing
*   We use FactoryGirl/Faker for generating fake data in specs
*   We use Simplecov gem for keeping code well-covered with test
*   We use gems and mocks for testing all 3-d party vendors (rspec-sidekiq / stripe-ruby-mock)
*   Must have specs: model/feature/controller
*   For testing JavaScript use Poltergeist or Capybara Webkit
*   Use DatabaseCleaner

###### refs*:

[https://robots.thoughtbot.com/how-we-test-rails-applications](https://robots.thoughtbot.com/how-we-test-rails-applications)



* * *


#### CODE REVIEW

*   Be humble and polite. Assume everyone is attractive, intelligent, and well-meaning.
*   Ask questions and clarification.
*   Don't use sarcasm
*   Don't take it personally
*   During a review You should keep in mind next questions:

*   Any code duplicaton there?
*   Is code’s structure optimal?
*   Any potential bugs?
*   Is code efficient?
*   Is method/variable naming good?
*   Is class/function length fine?
*   I there any commented code? Why?
*   Is code readable?
*   Are there any tests written for this feature?
*   Any N+1 queries there?

*   Finish reviewning a pull request with a "Ready to merge" comment or similar.

###### refs*:

[http://pult.vertalab.com/pages/10](http://pult.vertalab.com/pages/10)
[https://www.kevinlondon.com/2015/05/05/code-review-best-practices.html](https://www.kevinlondon.com/2015/05/05/code-review-best-practices.html) 
[https://github.com/thoughtbot/guides/blob/master/code-review/README.md](https://github.com/thoughtbot/guides/blob/master/code-review/README.md)


* * *


#### Deployment


* * *


#### TOOLS

Depending on preferences developers could choose to use Emacs or Vim as their main IDE.

*   [Emacs Prelude](https://github.com/bbatsov/prelude)
*   [Vim](http://www.vim.org/)
*   [Atom](https://atom.io/)



* * *


#### Think twice on using those tools

*   [Active Admin.](https://github.com/activeadmin/activeadmin)
