# JavaSwingTimeline

This is the result from a university project where I was tasked with making a timeline with a GUI using Swing that could load and save data to a JSON file and have the user add new information or delete entries. The scenario that I chose for this project was a timeline of Super Mario games some of which are hardcoded in the JSON file for immediate use. The user is able to cycle through these entries once the application is launched. The timeline itslf is displayed using a TreeNode display that enumerates depending on the size of the JSON array making it dynamic.

There was an issue in using file directories for the json file to be read in so file may not work correctly from the JSONService.readJSON method. The approach I used was only useful when launched from my own machine using the "user.dir" file path. In later iterations this could be changed to ask the user where to load the file from instead, avoiding this issue entirely in theory.
