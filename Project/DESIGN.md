# Design Milestone

In this milestone, you will write a design proposal for a software engineering bot. That is, bad proposals *may be rejected* by the professor. So spend time in coming up with a good and crisp idea.

To help, [9 seed ideas](IDEAS.md), have been provided. You must base your project on one of the seed ideas, or get an approved idea (by creating a pull request). There is a maximum of 3 teams that can work on the **same seed idea**.

You will also be working in a team of students. Remember to [sign up](https://docs.google.com/spreadsheets/d/1Xe5S04WI6UXBjtovKCBJ9S5o2EfuSydSs6YHw30rwuo/edit#gid=0) for teams.

The proposal will be structured to include the following items:

* Problem Statement
* Bot Description
* 3 Use Cases
* Design Sketches
* Architecture Design
* Additional Patterns


## Problem Statement

Remember, we are solving problems in the software engineering domain. This does not include problems, such as finding a parking spot, but it may include problems such as forgetting api tokens, drudgery associated with manually creating REST calls, difficulty in executing certain command lines tools, or not wanting to wake up at 3am to restart a server that crashed. 

What is the problem? *Why* is it a problem?

This should be a good paragraph or two.

## Bot Description

What does your bot do? Why is a bot a good solution for the problem?
Does your bot have a converstation with users (e.g. hubot), or does it just response to events (e.g., coveralls bot on github)? Does your bot fit in one of the categories we talked about in class? A code drone vs documentation bot?

This should be a good two paragraphs.

Finally, devise a *tagline* for your bot, a simple phrase that captures the entire essence of the bot and your project.

### Use Cases

A use case is a way to describe a task that a user wants to perform and the required sequence of steps needed to accomplish that task. It also includes possible error states. For more information about use cases, [see slides](https://docs.google.com/presentation/d/1Y_SZmR57sDtV1TEF2q9b35bBbGhI7a-E9VwqBEIe1xA/edit#slide=id.g136dba642e_2_227).

Based on your design, describe **at least three use cases** that describes the primary functionality of your bot.

This is an example use case:
```
Use Case: Create a meeting
1 Preconditions
   User must have google calendar api tokens in system.
2 Main Flow
   User will request meeting and provide list of attendees [S1]. Bot will provide  possible meeting times and user confirms [S2]. Bot creates meeting and posts link [S3].
3 Subflows
  [S1] User provides /meeting command with @username,@username list.
  [S2] Bot will return list of meeting times. User will confirm time.
  [S3] Bot will create meeting and post link to google calendar event.
4 Alternative Flows
  [E1] No team members are available.
```

You can think of this as a set of conversations/interactions you want to be able to support with your bot.

### Design Sketches

* Create a wireframe mockup of your bot in action.
* Create a storyboard that illustrates the primary task that a user undergoes with bot.

## Architecture Design

* Create a diagram that illustrates the components of your bot, the platform it is embedded in, third party services it may use, data storage it may require, etc.
* Describe the architecture components in text.
* Describe any constraints or guidelines that should be established in building software for your architecture (e.g., a bot cannot send data from one user to another user).
* Describe any additional design patterns that may be relevant for your bot design.

This section should be several diagrams + paragraphs of text. This is the opportunity to really think through how you might build your system. Consider all the criteria listed here in your description. Generic architectures that do not properly reflect a solution will receive low scores.

## Submission

Create a team repository for your bot, using the assigned github repository.  In your README.md, list all team members and their unity ids. Add a DESIGN.md document (linked from README.md) with the following materials included. 

### Deliverables

* Problem Statement (15%)
* Bot Description (10%)
* Use Cases (15%)
* Design Sketches (30%)
* Architecture Design + Additional Patterns (30%)

**Draft DUE:** FRIDAY, SEPTEMBER 20, before midnight.

You must have completed your problem statement and bot description.

**Final Design DUE:** FRIDAY, SEPTEMBER 27, before midnight.


