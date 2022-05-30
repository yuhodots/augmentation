# Image-augmentation
Reproduce Manifold Mixup(Verma, Vikas, et al.) and AugMix(Hendrycks, Dan, et al.)

## How to Run

### Manifold Mixup

```shell
cd mixup
./run.sh
```

### AugMix

```shell
cd augmix
./run.sh
```

## Results

### CIFAR-100

|                                 | Reproduce | Paper  | Clustering quality |
| ------------------------------- | --------- | ------ | ------------------ |
| ResNet-20                       |           | -      |                    |
| ResNet-18                       |           |        |                    |
| Manifold Mixup, PreActResNet-20 |           | -      |                    |
| Manifold Mixup, PreActResNet-18 |           | 79.66% |                    |
| AugMix, PreActResNet-20         |           | -      |                    |
| AugMix, PreActResNet-18         |           |        |                    |

### miniImageNet

|                                 | Reproduce | Clustering quality |
| ------------------------------- | --------- | ------------------ |
| ResNet-20                       |           |                    |
| ResNet-18                       |           |                    |
| Manifold Mixup, PreActResNet-20 |           |                    |
| Manifold Mixup, PreActResNet-18 |           |                    |
| AugMix, PreActResNet-20         |           |                    |
| AugMix, PreActResNet-18         |           |                    |

### CUB-200

|                                 | Reproduce | Clustering quality |
| ------------------------------- | --------- | ------------------ |
| ResNet-20                       |           |                    |
| ResNet-18                       |           |                    |
| Manifold Mixup, PreActResNet-20 |           |                    |
| Manifold Mixup, PreActResNet-18 |           |                    |
| AugMix, PreActResNet-20         |           |                    |
| AugMix, PreActResNet-18         |           |                    |

## References

- Manifold Mixup: https://github.com/vikasverma1077/manifold_mixup
- AugMix: https://github.com/google-research/augmix
- AugMix torchvision: https://pytorch.org/vision/main/generated/torchvision.transforms.AugMix.html#torchvision.transforms.AugMix
