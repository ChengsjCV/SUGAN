# SUGAN

Shijie Cheng, Lingfeng Wang, Min Zhang, Cheng Zeng, and Yan Meng

Paper: https://doi.org/10.3390/s23177338

This is the implementation of SUGAN

## Requirements

- ### U-Net GAN

  - For detailed dependencies and corresponding version information, see UNetGAN_requirements.txt file.

- ### Gradient Normalization

    - Python 3.8.9
    - Python packages

    ```sh
    # update `pip` for installing tensorboard.
    pip install -U pip setuptools
    pip install -r GN_requirements.txt
    ```

## Datasets

- CIFAR-10 32×32

     http://www.cs.toronto.edu/~kriz/cifar.html

- CelebA-HQ 128×128

    http://mmlab.ie.cuhk.edu.hk/projects/CelebA.html

- Anime 128x128

    https://aistudio.baidu.com/datasetdetail/110820

## Citation
If you find our work is relevant to your research, please cite:
```
Cheng, S.; Wang, L.; Zhang, M.; Zeng, C.; Meng, Y. SUGAN: A Stable U-Net Based Generative Adversarial Network. Sensors 2023, 23, 7338. https://doi.org/10.3390/s23177338
```