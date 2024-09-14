
## Project: Interactive Virtual Fashion Trial Room

### Description:
The Interactive Virtual Fashion Trial Room is an advanced image-based virtual try-on system that allows users to visualize clothing items on their own photos with high fidelity. This project aims to create a realistic and user-friendly virtual try-on experience. We aim to build a high resolution try-on with accurate clothing warping, detail preservation, size adjustment, and style options (tucked/untucked), retaining human characteristics and offers an interactive UI for easy clothing selection and visualization.

### Tech Stack:
- Programming Language: Python
- Libraries:
  - TensorFlow/PyTorch for deep learning
  - OpenCV for image processing
  - scikit-learn for model evaluation
  - pandas, NumPy, Matplotlib, and seaborn for data manipulation/visualization, metric evaluation with existing
- Dataset: 
  - https://www.kaggle.com/datasets/adarshsingh0903/virtual-tryon-dataset
  - https://github.com/cuiaiyu/street-tryon-benchmark

### 20-Week Plan:
- (Week 1-3) Literature Review and Capability Assessment
- (Week 4-5) Data Preparation and Preprocessing
- (Week 6-8) Model Architecture Design
- (Week 9-11) Core Model Development
- (Week 12-13) Outfit Generator Development
- (Week 14-16) Model Evaluation and Optimization
- (Week 17-19) Interactive UI Development
- (Week 20) Documentation and Presentation



### Start:
1. **(Week 1-3) Literature Review and Capability Assessment:**
   - A skeleton code is given containing a model following the UNet architecture for the task of semantic segmentation. The dataset is composed of images of people in outfits, with the masks being the outfits they're wearing, The dataset was obtained from Kaggle.
   - Review recent papers on virtual try-on systems [List of papers](https://github.com/minar09/awesome-virtual-try-on?tab=readme-ov-file#Datasets-for-Virtual-Try-on)
   - Analyze 2D vs 3D approaches and their trade-offs according to time, resources
   - Identify key features and capabilities for our system
   - Decide on primary approach (2D, 3D, or hybrid) based on review.
