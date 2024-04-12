This is the folder containing the sample ckpt.pth file, which was trained with:
- [32,(8,6,4,3)] model structure;
- Pre-activated Blocks;
- Modified Shortcut;
- No Input Convolution;
- RandomCrop and RandomHorizontalFlip for augmentation;
- SGD (momemtum=0.9, lr=0.1, weight-decay = 5E-4);
- CosineAnnealingLR scheduler.
