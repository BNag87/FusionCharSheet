# FusionCharSheet
A character sheet layout for a custom TTRPG played on Roll20.com

The game, Fusion, is based on several established TTRPGs. As it draws influence from different games, a unique character sheet is required to manage all of the relevant information in it.

## HTML/CSS
In order to use this code, it needs to be embedded in a game on Roll20 where the GM can manually set their rules. As it is, it will not work outside of Roll20.

As Roll20 currently does not allow the use of Javascript, HTML is used to define elements the players can interact with. Several buttons can call functions (or sheet helpers) that will perform dice rolls. The way they are called outside of this character sheet is through macros. So "/roll 1d20" would roll a single 20 sided dice, and display the result.
Names and IDs are often used in conjunction with other elements to perform skill checks.

The CSS, like other sites, formats the information properly. Of note is a tabbed sheet system that allows the player access to much more information about their character. Such as the weapons they use, currency they carry as well as their skill levels.

## Dice Rolls
Roll20 provides built in functionality that can be customised through both HTML and CSS. By use of a button, several custom macros can be fired, performing pseudo-random dice rolls. 
These are typically all based off of the player characters attributes that are set in game ahead of time.

For example, a character may wish to arm a block of C4 explosives. This would requires use of the "Demolition" skill that the player can invest skill points in.
The higher their skill level means they have a smaller chance of failure.

Dice rolls, regarding this particular skill, are d100 based. The GM sets a threshold and the player must roll below that threshold to have their action succeed.
So arming a block of C4 would be relatively simple, so the threshold would be set as '20'. A player with a skill level of '10' in demolitions would essentially have a +10 bonus to the score of their roll.
