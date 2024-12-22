# Major bugs

## Solo games save trouble
### Explanation
Solo games aren't saved if the game isn't in the original game directory or launched by multiples windows users such as admin or others users
### How
Use the saving methods in H&D Extended & Extended Vanilla (used to save multiplayer and addons) which save games variable in directories instead of the windows registry


# Minor bugs 

## Weird H in options
### Explanations
Weird H character in the menu option/controls just under the zoom settings
### How
Not known


# Features/improvement

## Blocked start when not admin regkey
**PLEASE CONSIDER THAT THIS NOT AFFECT THE ABILITY OF THE GAME TO RUN NORMALLY WHEN USED IN ALL THE OTHERS VERSIONS**
### What
Remove the condition which check if there is a registry variable created in the windows registry
### Why
This registry variable can only be created in admin mode, this modification can allow the game to be installed as portable program and launch without admin permissions (when not in admin, registry variables are stocked into current user section of the windows registry
### How
Remove/Shunt the condition who avoid the game to start in the line 1032 of initsystem.cpp at the line which has the « bad installation » dialog
