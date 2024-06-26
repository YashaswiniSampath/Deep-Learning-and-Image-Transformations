## Deep learning and Image Transformation

This project focuses on image transformations and deep learning using PyTorch. It involves creating and evaluating models on the CIFAR10 dataset, implementing a neural network with performance evaluation metrics, and adapting models to handle shuffled image patches \
\

<img width="573" alt="Screenshot 2024-06-27 at 12 41 37 AM" src="https://github.com/YashaswiniSampath/Deep-Learning-and-Image-Transformations/assets/44898518/772ec28f-f441-4f88-8ed6-fb21492dd6a5">

\

After testing various models like CNN, ViT, LeNet, VGG, and PEViT, we found that PEViT performed the best overall. Inspired by the paper "Human-imperceptible, Machine-recognizable Images," PEViT achieved impressive results, nearly matching performance on both standard CIFAR10 images and those with shuffled patches. Its unique architecture, which includes reference-based positional encoding, cleverly integrates positional information without compromising on its ability to handle shuffled data. This innovation allows PEViT to excel in both image recognition and encryption tasks, making it a standout choice for our project.
