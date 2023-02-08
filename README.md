# Training customized object detection model using Tensorflow Object Detection API

This repository provides hassle-free tutorial on training customizd object detection model via transfer learning using Tensorflow Object Detection API, based on Google Colab. 
 

This fork has the following changes
1. Works on Windows 10
2. COCO to TF Record: Import COCO files to TF Record files (that are suitable for use with object detection training)
3. COCO tiling utility: Used to break up large images (with annotations) into smaller images (tiles), and fix up the annotations to line up with the smaller images



## label studio

http://localhost:8080/projects/6/data/local-storage/6/9ee06b40-Day_1_Images_Flight_1_DSC09209_geotag_1.JPG


## Model training

### Training details

<https://www.tensorflow.org/guide/distributed_training>
<https://www.tensorflow.org/guide/checkpoint>


### Execution flow for training
[model_main.py]
    main
        [model_lib_v2.py]
            train_loop
                [inputs.py]
                    train_input
                        [image_resizer_builder.py]
                            build

?????????
                train_step_fn()
                    eager_train_step
                        _compute_losses_and_predictions_dicts(...) #model prediction is done here


??????????



