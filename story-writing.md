# Writing Project Stories

![New Stories][add1]

On Pivotal Tracker the tasks that need to be completed are called **stories**. 

This nomenclature reflects the nature of functionality in software development generally and in particular in [Behaviour Driven Development (BDD)](http://guide.agilealliance.org/guide/bdd.html) which is a form of software development we will be engaging in going forward. i.e.

> ##### This person wants this to happen if this or that happens, but only when this has already happend!

---

This guide is intended to help you write stories that are as clear and useful to other members of the team as possible. **Remember**, when you write a story, *even if it's just for you*, try to follow best practices. Doing so:
    
- will make the job easier for you and everyone else in the team because they and you can just get on with the task at hand
- There will be no need to engage in a back and forth about clarifying this word or that phrase
- There will be no down time on important stories that are rejected due to unclear or clumsy wording.

---

## User Stories

#### What is a User Story?

A User Story is simply a way of writing stories.

#### Why user stories?

They encourages the writer (_and the person working on the story_) to keep the user's needs and goals in mind as they work.

User stories take this form:

```
AS A user
I WANT TO do this thing
SO THAT I can do that thing
```

Let's break this down to understand it better.

-  `AS A user`
    - The user in this sense will be one of the defined user personas (or a group of user personas) e.g. "As a School Leaver", "As a Learner", "As an Education Sector Client"  - [see the task](https://www.pivotaltracker.com/n/projects/1374910/stories/98097686).
- `I WANT TO do this thing`
    - This is the specific task that the user **needs to do** to achieve their wider goal.
        
    Don't be confused it may well be that the user doesn't really *want* to do what the story says e.g.
    
    > As a learner I want to sign up so that I can receive updates on new courses

    Sure, maybe I would rather receive updates on new courses without having to sign up first and so I don't _really_ "want" to sign up, but that is the way the system works right now and so, to achieve my wider goal of receiving updates, I must sign up.

- `SO THAT I can do that thing`
    - This is the tangible value to the user. Adding this piece of information is


## Add a Story

![Add a story][empty]

#### The first thing you have to do

is decide whether your story is an Epic, a Feature, a Bug, a Chore, or a Release.

- **Epics** are very large stories that comprise multiple tasks. They cannot be completed without breaking them down further into lots of other stories. Epics are great starting point for focusing the direction of the rest of your stories.


### Start with the Epics

As a user I want to do this broad thing e.g.
As a potential learner I want to take a course about engineering 

As far as the user stories are concerned, this means that you can avoid things like: 

> "AS A user I WANT TO get better at French SO THAT I can live in France"

Sure, that's a story about the user and reflects their wants and needs but it is not do-able. Here, the definition of done is impossible to measure. 

### Break down Epics
By limiting the user's wants and goals to the needs of the business - force the user to accept that this is the way it has to be - stories can become more granular, testable, and the definition of done is more binary. 


### Add Acceptance Criteria

- Automated code tests are passing
- User Tests are Passing
- Sign-off

[More information on writing user stories (GOV.UK)](https://www.gov.uk/service-manual/agile/writing-user-stories.html)


[add1]: img/stories/add-story.png "Click to add a story"
[empty]: img/stories/empty-story-top.png "An empty story in Pivotal Tracker"