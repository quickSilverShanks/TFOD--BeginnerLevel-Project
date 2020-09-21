# TFOD--BeginnerLevel-Project
 A beginner-level Tensorflow Object Detection Project using tf v1.14.<br>
 <b>Credit</b> : The codes(with some local changes) are from the original repo : https://github.com/tensorflow/models/tree/v1.13.0<br>
 The image annotation tool 'LabelImg can be obtained from its original source : https://github.com/tzutalin/labelImg<br>
 <hr>
 The model architecture used for this project is "faster_rcnn_inception_v2_coco".<br>
 The model was trained locally for initial 234 epochs on "i7-8750H CPU @ 2.20GHz" + 8GB DDR4 RAM using tensorflow V1.14. For further improvement of model, it was trained on Colab till a total of 1000 epochs with GPU enabled.<br>
 The steps followed to train the model has been mentioned in the 'Read Me (Steps)' file in order to revise the steps or recreate the similar folder structure on future projects.<br>
 The Colab notebook is also in the repo with training outputs.
 <hr>
 It has been observed that after 1000 epochs of training its able to identify cards that are completely in view. In case of partially concealed cards, its able to make a few correct predictions. Perhaps a 1000 more epochs will enable even better prediction(an experiment for next github commit).<br>
 Sample Predictions:<br>
 ![pred1]./sample_predictions/prediction1)&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
 ![pred2]./sample_predictions/prediction2)&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
 ![pred3]./sample_predictions/prediction3)&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
 ![pred4]./sample_predictions/prediction4)&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
 ![pred5]./sample_predictions/prediction5)
