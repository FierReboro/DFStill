# DF-rawmod

	Spec_Rs contains the raws for reaction_other.txt
  		ex: [REACTION:BREW_GUAVA_WINE]
	        	[NAME:brew Guava Wine]
	P_Mtd contains the raws for entity_default.txt
  		ex: [PERMITTED_REACTION:BREW_GUAVA_WINE]
	Dv-inj contains the code for DFhack's devel/inject-raws

keywords:  

	*main* == Dwarf fortress main folder
	*world* == your World's save folder

	


Instructions for beginners:

A. is DFhack installed on your game and you want to use the new reactions on an existing save? If yes, then:
1. Make a backup of the world where you want to install these new raws. *Has risk of save corruption*
2. Copy the contents from Spec_Rs, and paste it inside \*main\*/data/save/\*world\*/raw/objects/reaction_other.txt.
3. ..Copy the contents from P_Mtd, and paste it inside \*main\*/data/save/\*world\*/raw/objects/entity_default.txt under the [MOUNTAIN TAG].
4. Open Dwarf Fortress then play your world. After it loads, and the DFhack console is ready, pause the game. Copy the contents from Dv-inj, paste it to the DFhack console, then enter. The console will ask you if you have made a backup of your save. After the console has finished processing the code, immediately save and exit the game without unpausing the game. *DO NOT USE QUICKSAVE* ("I don't know what will happen if you do")
5. After it's saved. Open your world, and the new reactions should be ready to use in the Still.

B. do you want to use the new raws on future worlds? If yes, then:
1. Copy the contents from Spec_Rs, and paste it inside \*main\*/raw/objects/reaction_other.txt.
2. Copy the contents from P_Mtd, and paste it inside \*main\*/raw/objects/entity_default.text under the [ENTITY:MOUNTAIN] tag.
3. Simply make a new world. "Tip: if you're experiencing crashes from starting on a new world, try to reduce the size of your Dwarf Fortress window, as small as you can if you like."
