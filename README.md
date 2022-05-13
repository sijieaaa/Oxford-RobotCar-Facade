# Oxford RobotCar Facade

[Building Facade Parsing R-CNN](http://arxiv.org/abs/2205.05912).

## Configuration

- This dataset is created based on the Oxford RobotCar Dataset (https://robotcar-dataset.robots.ox.ac.uk/)  and the Oxford Radar RobotCar Dataset (https://oxford-robotics-institute.github.io/radar-robotcar-dataset/)

- The *train* split contains 400 images, while the *test* split contains 100 images.

- There are 5 classes for semantic labels: { *window*, *door*, *balcony*, *shop*, *facade* }

- We also provide extra instance and panoptic labels.

- Palette: 

  |  Class  |      RGB      |
  | :-----: | :-----------: |
  | window  |  (255, 0, 0)  |
  |  door   | (255, 128, 0) |
  | balcony | (128, 0, 255) |
  |  shop   |  (0, 255, 0)  |
  | facade  | (255, 255, 0) |

## Citation

If you use this dataset in your research, please cite: 
```
@misc{https://doi.org/10.48550/arxiv.2205.05912,
  doi = {10.48550/ARXIV.2205.05912},
  url = {https://arxiv.org/abs/2205.05912},
  author = {Wang, Sijie and Kang, Qiyu and She, Rui and Tay, Wee Peng and Navarro, Diego Navarro and Hartmannsgruber, Andreas},
  keywords = {Computer Vision and Pattern Recognition (cs.CV), FOS: Computer and information sciences, FOS: Computer and information sciences},
  title = {Building Facade Parsing R-CNN},
  publisher = {arXiv},
  year = {2022},
  copyright = {Creative Commons Attribution 4.0 International}
}
```

## Download

- Google Drive: https://drive.google.com/file/d/1ASDkxdjPd3xVMeFq9R3HrxtYZIQz_B5s/view?usp=sharing
- Microsoft OneDrive: https://entuedu-my.sharepoint.com/:u:/g/personal/wang1679_e_ntu_edu_sg/EQztd88hEpNPk-tqVlYCaSABDhvNabf1P-I7Wnegup8EzA?e=QEYNp0

## Visualization
![viz](https://github.com/sijieaaa/Oxford-RobotCar-Facade/blob/main/assets/viz.png)

