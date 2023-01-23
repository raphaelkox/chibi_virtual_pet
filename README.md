This project is a study to create a simple "Tamagotchi" style virtual pet.
Prototyped originally using Gdevelop as a quick project.

The challenge here was to find a way to host all the compressed image data
in the PROGMEM region, as that is not handled by default by the screen.

Some pointer magic was used to achieve that.
