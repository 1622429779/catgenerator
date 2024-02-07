# catgenerator
This project is about a cat generator that uses python in maya, which gives the functions to change parts of the body, give base colors and start rigging with it.

!!!INSTRUCTIONS FOR CAT GENERATOR!!!
1. download the zip 'catGenerator' and unzip it.
2. open up the path  with ending: \catGenerator\scenes and open ''catGeneratorScene_research_v2"
3. open maya script editor
4. file-openscript-locate to the unzipped folder and locate to : \catGenerator\scripts. 
5. Open up researchproject2_Cat_v2.py
6. run the two arrows play button to generate GUI

*7. choose all pictures in \image folder BY NAME: ear-head-leg-tail-icons

''''''''''''''''''''''''''''''''''
do not save the scene after modifying!!! Will go wrong if saved attributes

''''''''''''''''''''''''''''''''''

Project introduction:
the Cat Generator gives you the freeness to modify and create a cat with given options.

Modeling:
There are 4 options for the face, ears and tail, along with 2 options for the leg type.
You are given the freeness to extend and shrink the arms and legs of the cat, can make the body fat or skinny,
and a special feature* is that you can curve any of the tails up and down to decide how your cat's tail would bend.

To change options, simply click on the icon which shows characteristics you want your cat to have.
To extend and shrink the given features (leg length, body thickness, arm length), click and drag the sliders in the GUI.

Coloring:
You can give color to the cat, which color can be chosen through the rgb layout at the bottom of the GUI.
Selct color, then press the button of the characteristic you want to generate.
Color options: the body base, the iris of the eye, the pupils of the eye, and the hat option given for ear type A.

Rigging:
To guide users in the process, each stage needs to be unlocked by completing the previous stage. Can be reversed with popped up icons.
Proceed to rigging stage and lock modeling tab. Can be reversed by clicking on the red popup button on Model tab when Model Tab is locked.
FreezeTransformationsandHistory all by once. Can do seperately. 
Select and deselect all visible icons by querying layer status.

Generate locator for the cat to indicate world position
Gnerate joint positions for the cat by calculating the bounding box of each body part.
*STILL TESTING*: select any joint, reorientate it, and add a main constraint to it.
*STILL TESTING*: combine all meshes but for tail. Currently haven't put commands in it yet.

     Directions: move in xyz directions by default 5. If pressed more than 3 times in a row, will decrease distance to 2 afterwards when pressed.
	*if any other icon in Rig tab is pressed, will default the direction value back to 5.*
	double clicking will let the obj move by 8.
When exiting, please do not save the scene! It will become messed up if the attributes changed.
