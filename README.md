/*
======================================================================================================================================================================
======================================================================================================================================================================
Fantasy Final v.1.1
Created by:  Brian Bui, Randy Le, Elizabeth Li
Due:  5 December 2015

This project was based off of Brian's Group Project 3 a.k.a. the "Simulat-inator" which is a turn based RPG.  The RPG allowed users to create and account, login,
create and fight monsters, and reference player logs and master logs.

The changes coming into this project includes:
	•  The creation of prototype functions.
	•  Cleaner overall program.
	•  While loops.
	•  A 7th function, that allows players to see the monsters in the registry and their "difficultly level".
		•  Difficulty was determined by the base damage.
	•  Minor bug fixes.

For easy reference, these are the 9 functions required of us:
	•  Main
		-  This function calls on the other functions, and loops until the user quits.
	•  displayMenu
		-  This function calls on the menu, which is fairly user friendly.
	•  getChoice
		-  This function ensures that a valid response is given, if a valid response is NOT given, the user will be redirected to the menu.
	•  registration
		-  This function allows the user to create a username and password in the registry.  
	•  login
		-  This function allows the user to log in, checking the username as a .txt file, and the password as the first line of the file.
	•  createMonster
		-  This function allows the user to create a monster.
	•  arena
		-  This is easily the most elaborate part of the program, it allows the user to fight against loaded monsters, created by the user.  The player has two skills
		to use:
			-  Sword Slash, a high percentage, medium damage attack.
			-  Fireball, a lower percentage, higher damage attack.
		The program loops until the player or monster is dead, and then uploads the results to both the player log and the master log.
	•  playerBuild
		-  This program asks for a player name, and then pulls up the player log.  If a player is not found, the user is redirected.
	•  adminBuild
		-  This program pulls up the masterBuild.
	•  monsterReg
		-  This is the latest/lastfunction added.  It allows the player to pull up monsters in the registry, and their base damage + difficulty level.

======================================================================================================================================================================
======================================================================================================================================================================

*/
