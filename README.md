# PTA: Piece-wise two-sample t-test augmented medical image segmentation

## Project Structure
```
PTA
├─ SGE_scripts
│    ├─ evaluate_on_host.sh
│    └─ train_on_host.sh
├─ acdc_data.py
├─ acloss_tf.py
├─ acloss_torch.py
├─ background_generator.py
├─ check_student_loss_work.py
├─ config
│    ├─ __init__.py
│    └─ system.py
├─ environment.yml
├─ evaluate_patients.py
├─ experiments
│    ├─ FCN8_bn_wxent.py
│    ├─ __init__.py
│    ├─ unet2D_add_bn_wxent.py
│    ├─ unet2D_bn_modified_dice.py
│    ├─ unet2D_bn_modified_wxent.py
│    ├─ unet2D_bn_modified_xent.py
│    ├─ unet2D_bn_wxent.py
│    └─ unet3D_bn_modified_wxent.py
├─ image_utils.py
├─ metrics_acdc.py
├─ model.py
├─ model_kl.py
├─ model_zoo.py
├─ prediction_contrast.py
├─ prediction_contrast_plot.py
├─ requirements.txt
├─ simulations.py
├─ test_circle_student_loss.py
├─ test_init_circle_mask.py
├─ test_kde_loss.py
├─ test_kl_loss.py
├─ test_loop.py
├─ test_student_t.py
├─ tf_test.py
├─ tfwrapper
│    ├─ __init__.py
│    ├─ layers.py
│    ├─ losses.py
│    └─ utils.py
├─ train.py
└─ utils.py
```

## Requirements 

- Python 3.5 (tested with Python 3.5.3)
- Tensorflow (tested with tensorflow 1.12)
- The package requirements are given in `requirements.txt`

## Dataset

- Automated Cardiac Diagnosis Challenge (ACDC 2017)
- Type: 3D MRI 
- Size: about 1TB
- Download link: https://aistudio.baidu.com/aistudio/datasetdetail/56020
