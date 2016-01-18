# Sessions Mobile App

Sessions is an open source mobile app that manages personal fitness challenges.
Fitness challenges are defined in the [challenge spec](https://github.com/sessions-io/challenge-spec).
Fitness challenges can be in one of 3 states: 'saved', 'active' or 'complete'
A saved challenge is something you want to do, but are not ready for yet.
An active challenge is something you are trying to achieve right now.
A completed challenge is a challenge where you met the criteria for completion.

The natural flow is to:

  1. discover a challenge (on a blog for instance)
  2. save/bookmark the challenge
  3. decide you want to attempt it
  4. perform activities to complete it
  5. challenge is completed when criteria is met
  
While this is the most natural flow, there are other cases.
You might "give up" on an active challenge and decide to save it for later or ditch it.
You might remove a saved/bookmarked challenge if you decide later you dont want to do it.

The primary goal of our sessions app is to be a place where it is easy to:

  1. view and evaluate challenges you have saved "do i want to start this now?"
  2. monitor the progress of active challenges "how far along am i? what do i need to do today? can I wait until tomorrow?"
  3. view the completion of past challgens. "how did i perform in challenges last week?" 

## Progress tracking

A key design constrait is that progress is detected and evaluated automatically. We integrate with modern wearable/sensor technology and software to track progress. The system atuoamtically promotes an active challenge to a completed one. The mobile app sends an optional notification when moving a challenge to the completed state.
