# gui_object_detection

this is a temporary project on how to train a model which is capable to detect differen kinds of gui elements, i.e. comboboxes, buttons, text fields, in screenshots.

aim: as a hobbyist i want to gain practical experience in the following task: generate a modell that can detect gui elements of a particular desktop application (google for "Object Detection for Graphical User Interface")

- generate annotated data, e.g screenshots with bounding boxes around gui elements and type of gui element
- how to train a model
- check model results


ATTENTION: This is a temporary project and will be deleted

Links:

Links-Academic (arbitrary):
https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=9631239
https://eprints.whiterose.ac.uk/145601/1/gui-component-recognition.pdf

Links-Open Source/Hobbyist:



Structure:
docs - contains documentation


Current tasks:
1. run "model web-form-ui-filed-detection" from user "foduucom" from website "huggingface" against various screenshots from 2-3 public available web sites like:https://www.darmstadt.de/rathaus/online-dienste/terminvergabe-einwohnermeldeamt
2. train model with data (extraction of data and annotation, ...)

Questions:
1. is there a public available workflow to train a modell vor objekt detection of gui elements from screenshots which can be managed by hobbyists
2. data preperation: color depth, screen resolution
3. can we uses special characteristics of screenshots that can be used in the training process, e.g an enabled text field might have a defined color, usage of heuristics (e.g all elements have vertical and horizontal lines)
