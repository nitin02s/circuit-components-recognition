# circuit-symbol-detector
Give it a circuit, it'll give you the components with their locations.

Works on hand drawn.

## cli
call img.py -p PATH/TO/IMG
it will store components in dump folder
everything else is self explainatory

## model
pre trained model in colab_images/model3.h5 pretty inaccurate

## telegram integration
golang: put your bot token in the imgserver.go file and change the basePath variable to wherever your folder is
when you run it, if you send the bot an image, itll respond with segmented components