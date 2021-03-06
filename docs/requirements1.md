# Collaborative Event/Task Manager

A webapp that allows cooperative event coordination and/or task management.

## Problem

There are many options out there for calendar and task management applications, but most don't allow for a collaborative approach or delegation-based planning.

## Objective

To create an easy-to-use app that combines event coordination and task management, and allows it to be approached in a cooperative way. This will increase the efficiency of workflow and planning for groups/big events, and allow different settings for volunteering/mandatory tasks and events.

The idea is to make a simple, effective hierarchical structure to planning: Events>Tasks>Subtasks.

Ideally, this webapp would be useful to very wide-range of users, from organizations planning volunteer events to a group of friends planning a birthday party.

## Outline

Users will be able to make an account, and once that's done, they'll be able to create events or tasks. The site will have a hierarchical structure, so if the user creates an event, they will be able to nest a series of tasks within that event. Tasks will also be broken up into subtasks (if needed) for greater clarity and efficiency. The user will also be able to invite other users "to" the event, and once the invitees have accepted, they'll be able to assign other users to specific tasks.

Users will also be able to add descriptions and time tables to any event/task/subtask, and comment on them if they are a part of the event/task but not the creator.

## User Stories

As a nonprofit event manager, I want to be able to set up an event and denote all of the tasks that need to be completed for the event, and allow other people to sign up and volunteer for them.

As a parent, I want to be able to plan a list of tasks that need to be completed by my spouse and children while I'm gone on a trip.

As a club president, I want to be able to make a group, invite the members of my club, and then easily plan events where I can delegate tasks to the other members.




##Data

Users will be able to input parameters for creation of events/tasks/subtasks, descriptions and time tables for each, as well as comments.

The website will output a clean, easily accessible hierarchical structure that is easy to move through and edit as you go.

## Stretch Goals

1. Include the functionality to create groups, which will be useful in many situations (workplaces, academics, houses with multiple tenants, etc). Users will be able to create events/tasks that are strictly visible only to invited group members.

2. Allow for tasks/events that repeat over a set length fo time.

3. Allow for task designation that rotates with repeated events/tasks (ex: a rotating task list for a workplace so that workers don't do the same repetitive task each day).

4. Allow for google calendar integration.

5. Include functionality to make groups/events/tasks public or private.

6. Include functionality to make events/tasks specifically designated by an admin user (who creates the task) or open to volunteers instead.

## Design

Not yet decided, but the general idea is to make something that is minimalistic, with an overarching color scheme that creates a unique visual identity.

## Directories

Ideally, a simple combination of DIST and SRC directories, each containing html, css, and js files. This will necessitate the use of some tooling (compilers especially). The deployment process will also have to involve something like heroku that will allow for a more complex file hierarchy.

## Wireframe

Not yet decided.
