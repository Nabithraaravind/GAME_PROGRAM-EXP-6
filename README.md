# GAME_PROGRAM-EXP-6
## Implement the AI random movement.

## Name : A.NABITHRA
## Reg no : 212224230172

## AIM :
Implement the AI random movement.

## Algorithm:
Step:01 Create a Character Blueprint.
<BR>
Step:02 Create a Blackboard.
<BR>
Step:03 Open the Behavior Tree editor.
<BR>
Step:04 Create Behavior Tree nodes for the following, 
<BR>
 "Selector" node: Controls the execution of child nodes.
<BR>
 "Service" node: Monitors and updates values in the Blackboard. 
<BR>
 "Sequence" node: Executes child nodes in sequential order. 
<BR>
 "Random" decorator: Randomly selects a child node to execute. 
<BR>
 "Move To" task: Moves the AI character to a specified location.
<BR>
Step:05 Set up the Blackboard with vector key and bool keys and save it.
<BR>
Step:06 Set up the AI character Blueprint with the help of AI controller component.
<BR>
Step:07 Set the AI controller and behavior treeiIn the Possess node, select the AI Character Blueprint you created and drag off the AICharacter reference and search for “Use Blackboard”
<BR>
Step:08 Set up the NavMesh and boundaries, we can adjust the size and position to cover the desired play area.

## OUTPUT :
<img width="505" height="359" alt="image" src="https://github.com/user-attachments/assets/2fa47a30-10f1-4102-b575-b08f3c579b04" />
<img width="505" height="197" alt="image" src="https://github.com/user-attachments/assets/a0a12554-3cc5-4067-8261-78a9155c0d04" />
<img width="505" height="181" alt="image" src="https://github.com/user-attachments/assets/797c652f-100d-4d00-98b2-6b0a022c4060" />

##  RESULT :
Thus, the AI concept to the actor for a random movement is implemented.

