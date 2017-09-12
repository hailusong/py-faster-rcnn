### Disclaimer

Forked from https://github.com/rbgirshick/py-faster-rcnn

# *Faster* R-CNN: Two-class Output and ResNet101 Option

### Differences between train-net and test-net
1. Train-net has these elements (not in test-net)
    - LR parameters, e.g. lr_muti
    - Weight initializer, e.g. Gaussian mean = 0, std = 0.001
    - Drop-out layers
2. Test-net has RPN as part of the net model
    - which train-net doesn't have
