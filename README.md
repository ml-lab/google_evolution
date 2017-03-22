Paper: https://arxiv.org/abs/1703.01041

1. Overwrite `{TORCHVISON_PATH}/\_\_init\_\_.py` with new one.
2. Copy `evolution.py` to {TORCHVISON_PATH}.
3. `python main.py -a evolution {CIFAR10_DATA_DIR}`

cf. How to know {TORCHVISON_PATH}?
```
import torchvision
print(torchvision.__file__)
```

Note.
Channel number is not in the paper. It is set by me.
