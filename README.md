# GDIM32 In Class Activities
## Week 1
### Activity 1
Advice: 


- Manage your time wisely by thinking about how long coding the minigame will take. Make sure to start early and avoid trying to submit the assignment too close to the deadline because technical errors may occur.
- Use tech support/office hours to your advantage.
- Use the Unity documentation to search up different types of codes and their functions.

### Activity 2
Q1: x is 10.


Q2: x is 2.


Q3: The lines of code calls the method "PrintMessage()" and that prints the message "hello world" in the debug log for every frame.


Q4: MonoBehaviour


Q5: The lines of code calls the method "PrintMessage()" with the argument 10 in the parenthesis. The method prints "x = 10" in the debug log.


Q6: The first highlighted line is the argument and the second highlighted line is the debug log method parameter.


Q7: Transform is a class and is used as an object instead.


Q8: _playerTransform

### Activity 3
[Group 14 MG1 Breakdown Google Doc](https://docs.google.com/document/d/1ZloeI2O3HLCZUm7UvvfKdylog4EuKHg3eZPcW1Tevz0/edit?usp=sharing)




## Week 2
### Activity 1
<img width="991" height="742" alt="Screenshot 2026-01-13 180420" src="https://github.com/user-attachments/assets/2e7fd6f8-01ff-4bc7-a486-5ad7e3300498" />

### Activity 2
[In-class activity Commit](https://github.com/UCI-GDIM32-W25/mg2-rbcfeng/commit/a3c4ade6d514f282262ce9405bbb5d1715178d7c)

I created the Player, Coins, and GameController scripts, coded the player jump movement, and added colliders and rigidbodies to the player, coins, and the ground. I've also add the points UI on the canvas.




## Week 3
### Activity 0-2
Frances Kim

### Activity 3
<img width="965" height="750" alt="Screenshot 2026-01-20 185045" src="https://github.com/user-attachments/assets/8253422c-1361-4f0b-b7a3-92c5b1074421" />




## Week 4
### Activity 0
Frances Kim

### Activity 1
The Locator objects disappear from the scene because the if statement in the Awake method in the Locator class is making sure that all Locators except one copy is destroyed.

### Activity 2
<img width="966" height="742" alt="Screenshot 2026-01-27 185632" src="https://github.com/user-attachments/assets/c36af64d-0e08-4ab6-bccc-50700cb67917" />

### Activity 3
[In-class Activity Commit](https://github.com/rbcfeng/HW4/commit/1e0098e0fda21348c298d5291dbdbe83e31f1ca8)

I created the Unity project, added sprites on the scene, added jump movement, added the points UI, and added the scripts.




## Week 5
### Activity 1
I noticed that there was a definition for the _durability member variable for each class that inherited from the Item class. To make it better, it would be nice to have the _durability member variable defined in the parent class, which would be in the Item class. That way, each child class can inherit the definition of _durability based on the item they are and edit the value. Something that would be even better would be to have each item type as a scriptable object, so that designers can edit each statistic without having to look at the code.

### Activity 2
The classes that represent model would be the EnemyStats and ItemW5Demo2 classes because they manage the ScriptableObjects game data. The classes that represent the view would be the DialogueBubble and InventoryUI classes because they manage what the player sees, which would be the dialogue for each sprite and the inventory UI. The classes that represent the controller would be the PlayerW5Demo2 and the EnemyW5Demo2 because they are the logic that makes the player move and when the enemy shows dialogue.

### Activity 3
#### Scenario 1
The beats are scriptable objects that describes the type of notes, the speed, and the appropriate keys pressed. There should be prefabs of the beat sprites.
#### Scenario 2
The MVC pattern is used, as the model would be the different weapon stats, the view would be the UI that shows activating abilities, and the controller would be how each weapon functions when it is used by the player.
#### Scenario 3
We would need to use the finite state machine with C# enums for player animations, inheritance for an item parent class with plants, seeds, rocks, and other types of items, a singleton as a locator for the player, and scriptable objects to define each type of plant and other items. For inheritance, the abstract classes could be the different types of plants that could be planted and the interface classes could be the items that can be broken. We would use the MVC pattern since the scriptable objects are the models, the UI and audio can be the view aspect, and the controller can be how long the plant is ready to harvest.

### Activity 4
Attendance: Rebecca Feng, Frances Nareh Kim, Landon Peev Xwm Her, Nansong Sun

Proposal: [Final Project Proposal First Draft](https://docs.google.com/document/d/12oXcMbRqu-4vIfI7XU0rpLQhKyyF9Gy7RNBljYCJIrA/edit?usp=sharing)
