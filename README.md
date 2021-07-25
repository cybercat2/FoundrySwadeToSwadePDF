# FoundrySwadeToSwadePDF
Utility to convert Foundry Swade character .json files to Swade character sheet pdf files.
Code is written in python version 3.7.3, and runs on Raspberry Pi OS version 10 (buster).

Current revision - Foundry2pdf is 0.2 beta. 
json files are exported from Foundry 8.8. 
game subsystem is Peginc Swade 0.19.5.

Known bugs - 
  die modifiers aren't handling 0 mod correctly. Will be fixed in 0.2 (soon). DONE 7/25/21

  PDF file is giveaway from Peginc, and I'm only Annotatiing them, not changing them, but i probably should get permission to use, or workaround (version 0.2.5).

Instructions - either pass your json file in command line param, or copy your json into "default.json", or run in IDE
and edit input file. Will add file picker in version 0.3 (fairly soon)

Will test on Win10 in near future (version 0.4).
