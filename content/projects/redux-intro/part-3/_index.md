---
_db_id: 551
content_type: project
flavours:
- javascript
- typescript
from_repo: projects/redux-intro/part-1
prerequisites:
  hard:
  - topics/redux-thunks
  - projects/redux-intro/part-1
  - projects/redux-intro/part-2
ready: true
submission_type: continue_repo
tags:
- redux
- redux-thunks
title: 'Intro to Redux for home automation: Party mode with thunks'
---

## Instructions

Now one super cool thing about redux is that you don't really have to dispatch actions one at a time. You can have an action with side effects, and those side effects can dispatch other actions!

There are two main ways to handle side effects in redux. Thunks and Sagas. Thunks are the easy way, and they are worth understanding before moving onto sagas.

Your mission is to create a few more actions that use Thunks to combine a few of your existing actions. 

Create a thunk called `PARTY_MODE` that kicks off a few other actions that you have already implemented. You could also create some new actions that might contribute to a good party. Eg Party mode might dim the lights, turn on the disco ball, and change the volume of the door bell.

Make at least one more thunk in the same way. For example you might have a `GOOD_MORNING`thunk that starts playing soothing morning tunes and turns the kettle on. 

What combinations of actions would you want to trigger? Get creative :)