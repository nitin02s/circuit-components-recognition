# circuit-symbol-detector

![](https://github.com/nitin02s/circuit-components-recognition/blob/master/Demo.gif)
Give it a circuit, it'll give you the components with their locations.

Works on hand drawn.
please create a folder named dump in the same directory

## cli
call img.py -p PATH/TO/IMG
it will store components in dump folder
everything else is self explanatory

## model
pre trained model in colab_images/model3.h5 pretty inaccurate

## telegram integration
golang: put your bot token in the imgserver.go file and change the basePath variable to wherever your folder is.
Run it and send the bot an image, it'll respond with segmented components.
