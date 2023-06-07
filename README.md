# Building-ensemble-of-Resnet-for-dolphin-whistle-detection
Building ensemble of Resnet for dolphin whistle detection

in dolphin_main.py you have to modify the following lines for extracting the different data augmentation approaches:

Define data augmentation flags

data_augmentation_configs = [

{

    "apply_random_shift_with_black_or_wrap": True,
    
    "apply_symmetric_alternating_diagonal_shift": False,
    
}
]
