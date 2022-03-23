# Image_Fake_Segmentation_Model
## Architecture
We implement three models, including: Classification (ResNet50), Segmentation (modified UNet) and Unification (unified modified UNet).
+ ResNet50 is chosen for the classification task. The ResNet50 architecture is shown in Figure 1.
+ Segmentation network is plotted in Figure 2.
+ A proposed model that merges the two models above into a single model called umUNet (unified modified UNet). umUNet is depicted in Figure 3.

<p align="center">
  <img src="pictures/ResNet50.png" width="800" alt="accessibility text">
  <img src="pictures/mUNet.png" width="800" alt="accessibility text">
  <img src="pictures/umUNet.png" width="800" alt="accessibility text">
</p>


## Result


![image](https://user-images.githubusercontent.com/67592591/144274056-e1030a9f-db4c-4a34-be0f-10d844b5f7a1.png)

Compare the predictions of two models: mUNet and umUNet. Each column is a data sample, while the rows represent the input image, surface label, mUNet surface prediction and umUNet surface prediction, respectively. As we can see, the segmented umUNet regions are sharper than those of mUNet.

## Citation
```
@article{
  title={Modified CNN model-based Forgery Detection applied to Multiple-Resolution Tampered Images},
  author={Thuong Le-Tien, Duy Ho-Van, Nhu Pham-Ng-Quynh, Hanh Phan-Xuan and Tuan Nguyen-Thanh},
  journal={NAFOSTED Conference on Information and Computer Science (NICS)},
  year={2021}
}
```
