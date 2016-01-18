# Sessions Mobile App

Sessions is an open source mobile app that manages personal fitness challenges.
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

## Progress tracking

A key design constrait is that challenges are automatically evalauted
We integrate with modern wearable/sensor technology and software to track progress.
The system atuoamtically promotes an active challenge to a completed one.
