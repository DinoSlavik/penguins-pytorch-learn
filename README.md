There should be file structure like this:
```
.
├── NN
│   └── Penguins
│       ├── best_model_200samples_ResNet18.pth
│       ├── data
│       │   ├── PTI1
│       │   ├── PTI2
│       │   └── PTI3
│       ├── ModelsFromScratch
│       │   ├── best_model_100samples_withoutcrop.pth
│       │   ├── best_model_200samples.pth
│       │   ├── best_model_200samples_ResNet_LastTry_FirstTeach.pth
│       │   ├── best_model_200samples_ResNet_LastTry_ForthTeach.pth
│       │   ├── best_model_200samples_ResNet_LastTry_SecondTeach.pth
│       │   └── best_model_200samples_ResNet_LastTry_ThirdTeach.pth
│       ├── penguins.ipynb
│       ├── tests
│       │   └── plots
│       └── transfer_ml.ipynb
├── README.md
└── requirements.txt
```

Where dir `NN` is home directory of our neural network.