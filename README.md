/*	-WHAT IS THIS?-
	This file adds optional material to "MPMB's Character Record Sheet" found at https://flapkan.com/mpmb/charsheets
	Import this file using the "Add Extra Materials" bookmark.
	-KEEP IN MIND-
	It is recommended to enter the code in a fresh sheet before adding any other information (i.e. before making your character with it).
*/

/*	-INFORMATION-
	Subject:	Feat
	Effect:		This script adds a feat called "Wardancer"
	Code by:	Toby
	Date:		2016-01-23 (sheet v9.9.9)
*/

var iFileName = "Wardancer [By Toby].js";
RequiredSheetVersion(10);

FeatsList["wardancer"] = {
	name : "Wardancer",
	source : ["HB", 0],
	description : "Your training in dancing gracefully has improved your reflexes and the fluidity of your movements, making you harder to hit. You gain proficiency in the Performance (Dance) skill. Your Charisma or Dexterity score is increased by 1 (up to 20). When not wearing armor, and not using a shield, you can add
your Charisma modifier to your AC",
	prerequisite : "Dexterity 13 or higher",
}
