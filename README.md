# Steel

- In this project, I aim to develop a state-of-the-art semantic segmentation neural network to address the critical task of localizing and classifying surface defects on steel sheets. [The dataset](https://www.kaggle.com/competitions/severstal-steel-defect-detection/overview), comprising 5506 unique images sourced from Kaggle, represents diverse instances of steel surfaces with varying defect scenarios.

**Objectives**

**Localization and Classification:**
- Implement a neural network capable of accurately localizing and classifying surface defects on steel sheets.
The defects fall into multiple classes [0, 1, 2, 3, 4], with 0 representing the background class.

**Dataset Overview:**
- The dataset contains RGB color images (*heigh $\times$ width $\times$ 3*).
 Masks are represented as a string with pairs of values that contain a start position and a run length. E.g. '1 3' implies starting at pixel 1 and running a total of 3 pixels (1,2,3).

 The dataset encompasses a wide range of scenarios, including images with no defects, single-class defects, and instances with multiple defect classes.
