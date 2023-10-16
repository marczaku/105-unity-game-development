# Assignment: Small Theft Auto

## Groups
This is a Group Assignment for 4 people per Group.

### Work Schedule
- Workdays 9:00 and 16:00 (or 18:00)

### Work Format
2 Groups of Pair Programming Students (2)
- One Student shares their Screen, and the other discusses how to approach the feature and feedback
- Switch the role of the active (typing) Programmer for each feature, but **at least every 2 hours**!
- There have to be regular commits from **EVERY TEAM MEMBER**
- Team Members without regular contributions will not receive a passing Grade
  
Swap the Pairs every other day, and make sure to work with every single team member of your team!

❌ Work alone, at your own pace!\
✅ Learn to communicate and discuss. It's the best way of improving code quality and team quality!

❌ Stick with the same team members every day!\
✅ Get to know each other and learn, whom it is easier to work with, learn to work with people that might not be so easy to work with and give each other feedback and the chance to improve!

❌ Commit after days, when everything is perfect!\
✅ Commit regularly, work iteratively (Get parts of a feature working, then improve)

### A Few more Tips
Don't work on the same Scenes, Prefabs or Scripts at the same time
- Create several smaller Scripts
- Create several smaller Prefabs
- Communicate who's working on what

Use Unity's Input Manager for Input
- Configure the Input and use `Input.GetAxis` and `Input.GetButton(Down/Up)`

Most Game Mechanics can be implemented through a Combination of:
- Physics: RigidBody, Collider, Trigger
- Unity Event Methods: Start, Update, OnCollisionEnter, OnTriggerEnter, FixedUpdate
- GameObjects: Instantiate, Destroy, SetActive
- Components: AddComponent, Destroy
- Scenes: LoadScene

Don't Google for solutions right away
- Companies hire Problem-Solvers
- Googling is a good and important tool as a back-up when stuck
- But you wouldn't Google the Solution to a Sudoku before trying to solve it yourself first, would you?
- Exception: MiniMap, Traffic, NPCs

## Basic Requirements:
A build of the Game is uploaded to [itch.io](https://itch.io)
- A short Gameplay Trailer
- At least two Screenshots
- A Game Description

At least 100 Points have been achieved.

## Excellent Requirements:
At least 140 Points have been achieved.

## Feature List

| Component | Feature | Score |
|-----------|---------|-------|
|Camera| Has a common perspective (First-Person, Third-Person or Top-Down) | 5 |
|Camera| If not First-Person: It Follows Player with a small Delay | 5 |
|Camera| BONUS: Camera smoothly rotates with the player | 0 |
|Player| Player can walk forward and backwards | 5 |
|Player| Player can rotate left and right | 5 |
|Vehicle| Player can enter Vehicles | 5 |
|Vehicle| Player can leave Vehicles | 5 |
|Vehicle| Vehicle can accelerate | 5 |
|Vehicle| Vehicle can brake | 5 |
|Vehicle| Vehicle can turn | 5 |
|Vehicle| Vehicle can move in reverse | 5 |
|Vehicle| Vehicle takes damage when colliding with other Vehicles or Walls | 5 |
|Vehicle| Vehicle has (visual) feedback when under a certain health threshold | 5 |
|Vehicle| Vehicle is destroyed when at zero health | 5 |
|Vehicle| Player is punished, if they are in the Vehicle when it is destroyed | 5 |
|UI| Game has a Main Menu and Instructions | 5 |
|UI| Player's Health can be seen | 5 |
|UI| Player's Currency can be seen | 5 |
|UI| Player's Score can be seen | 5 |
|UI| Player's equipped Item can be seen | 5 |
|UI| Player's Item's interactions until reload/recharge can be seen | 5 |
|Quest| Player can interact with a Questgiver-Object to receive quest | 5 |
|Quest| Player cannot interact with the Questgiver-Object if already on quest | 5 |
|Quest| Quest yields Currency Reward, if completed | 5 |
|Item| Player can switch Equipped Items between Hands, Item1 and Item2 | 5 |
|Item| Player can utilize equipped items to interact with Environment and/or Vehicles | 5 |
|Item| Items need to reload/recharge | 5 |
|Environment| There are buildings | 5 |
|Environment| There are paths/roads/streets | 5 |
|Effect| Effect exists that has an impact on the player while they are standing in the Effect | 5 |
|Effect| Effect is spawned by destroyed vehicles | 5 |
|Effect| Effect extinguishes after a while | 5 |
|Heal| Heal Powerups exist that heal the Player by a certain amount when collected | 5 |
|Hazard| Hazard exists that makes the Player lose the game if touched | 5 |
|GameOver| A Text is displayed. The player respawns after a few seconds. They lose half of their currency. | 5 |
|SavePoint| SavePoint-Powerups exist that save the Player's Progress if they are not on a quest right now. When loading, the player's Health and Currency is loaded and they spawn at the SavePoint that they touched last. | 5 |
| Total: | | 175 |
-------------------------------

## Bonus:

### BONUS: Traffic
There should be a continuous perception of vehicles navigating over the Map. The vehicles can run on pre-scripted paths, but they should give some impression of randomness/unpredictability.

### BONUS: NPCs
There should be a continuous perception of other NPCs navigating over the Map. The NPCs can walk on pre-scripted paths, but they should give some impression of randomness/unpredictability.

### BONUS: Minimap can be seen:
See, if you can find and utilize some free assets/scripts. The Minimap should show the environment and move with the player's position.

### BONUS: Split Screen
Make the Game SplitScreen with two controllable players
