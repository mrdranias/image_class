# image_class
modular_classifier
directory structure

```bash
home_dir
|
├── imagedata
│   ├── __init__.py
│   ├── image database stored locally
|   └── dataset_selection classes
│
├── output_dir
│   ├── category layer output vector
│   ├── n-k feature layers, flattened as vectors
│   ├── visualizations
│   └── output_stats
│
├── config_dir  
│   ├── __init__.py
│   └──config.py 
│
├── preprocessing
│   ├── __init__.py
│   └── preprocessing_classes
│
│
├── neural_network
│   ├── model_parameters
│   ├── network_class_info
│   └── saved weights
│
├── nn_predict.py
├── nn_train_bb.py
└── readme.md

```
