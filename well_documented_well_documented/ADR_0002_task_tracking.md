# Task Tracking

* Status: proposed
* Deciders: @jfahne
* Date: 2024-08-31

## Context and Problem Statement

How can this project track tasks in plain text files checked into the VCS?

## Decision Drivers

* Plain text
* Supports Kanban style task tracking

## Considered Options

* Vanilla markdown todos
* [todo.md](https://www.github.com/todomd/todo.md)
* [nb todos/tasks](https://xwmx.github.io/nb)
* Tasks as markdown files. Swim lanes as directories.

## Decision Outcome

Chosen option: "Tasks as markdown files. Swim lanes as directories", because it is flexible enough to fully capture a kanban board while still being simple enough to track in VCS easily.

### Positive Consequences 

* Full capture of Kanban methodology
* Entirely plain text
* No overhead to start using

### Negative Consequences

* No obvious kanban visualization exists for this set up.
* Unsure how this will connect with a calendar.

