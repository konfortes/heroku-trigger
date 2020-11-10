# heroku-trigger

## What

This repo has some npm commands to trigger actions in apps deployed to Heroku by making an http call to them

## Why

Heroku puts its free dynos into idle mode after some time, therefore, in-app scheduled tasks can not be used.
I could use npm scripts that are able to be scheduled (using the Heroku Scheduler add-on) but the thing is it can only run scripts that are not evaluated as part of the app itself.
