# Polyp-Segmentation-ISBI2023

Code will be released if the paper is accepted by ISBI2023.

## Model parameters VS inference speed
![result](https://github.com/suyanzhou626/Polyp-Segmentation-ISBI2023/blob/main/figs/params_vs_fps.png?raw=true)

## Experiments
### Quantitative results on learning ability.
![result](https://github.com/suyanzhou626/Polyp-Segmentation-ISBI2023/blob/main/figs/learning%20ability.png?raw=true)

### Quantitative results on generalization ability.
![result](https://github.com/suyanzhou626/Polyp-Segmentation-ISBI2023/blob/main/figs/generralization%20ability.png?raw=true)

### Quantitative results of different methods on multiply-add operations (MACs), model parameters (Params), and Speed (FPS).
![result](https://github.com/suyanzhou626/Polyp-Segmentation-ISBI2023/blob/main/figs/model_parameters_MACs_FPS.png?raw=true)

Note: we eval the speed in a PC with GeForce 1080Ti, the code for eval speed can be found in [here](https://github.com/suyanzhou626/Polyp-Segmentation-ISBI2023/blob/main/utils/eval_speed.py) .


## Visualization
![result](https://github.com/suyanzhou626/Polyp-Segmentation-ISBI2023/blob/main/figs/visualize_model_prediction.png?raw=true)


## Thanks to the repo
+ [PraNet](https://github.com/DengPingFan/PraNet/blob/master/lib/PraNet_Res2Net.py)
+ [UACANet](https://github.com/plemeri/UACANet) (especially, python version evaluation toolbox.)
