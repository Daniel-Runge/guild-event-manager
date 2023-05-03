# guild-event-manager
The Guild Event Manager (GEM) is a small project to manage guild events for Never Ever Again on Silvermoon.

The goals for the project are as follows 

- [ ] Simple webapp for creating events and signing up, similar to events managed through, for example, Google Forms
- [ ] Basic Discord integration, either as a webhook or a discord bot service to advertise for coming events
- [ ] WoW addon to handle invites and maybe ingame management of the guild

## Developer setup
GEM will be using cloud based infrastructure and architecture. The cloud provider will most likely be AWS using Terraform configurations. Most likely using Lambdas, but EC2 is still on the table for simplicity (Which would use Docker).

### Learning goals
The immediate learning goals for this project are primarily, but not limited to the following:

- Git, Git hooks, GitHub Actions, GitHub Projects
- AWS & Terraform
- Whatever programming languages we need (JavaScript, Python, Lua)

Furthermore, an imperative goal of the project is to create proper documentation as well as proper unit, integration, and usability tests.

## Problem analysis
Domain class brainstorm

> user, character, tournament, event, mythic key, rating, class, character role (tank, healer, damage), user role (organizer, participant), party, score time, history, guild

Pageviews brainstorm

> create profile/user, login/logout, profile, create event, event sign up/opt out, event list

