# Car Tracking in Videos
This project applies estimation, detection, and learning concepts to track cars in video sequences. The goal is to extract relevant features from the LaSOT (Large-scale Single Object Tracking) dataset, apply dimensionality reduction techniques, and use classification methods to track a single object (car) across frames in a video.

The primary objective is not to obtain the best tracking solution but to demonstrate understanding of the concepts, methods, and mathematical notations taught in the course.

## LaSOT Dataset
The LaSOT dataset is a large-scale dataset specifically designed for single-object tracking. It provides a variety of video sequences where a single object (in this case, a car) is tracked across multiple frames under various challenging conditions, such as occlusion, illumination changes, and scale variations.

### **Dataset Access**:
You can access the dataset from the [LaSOT official website](http://vision.cs.stonybrook.edu/~lasot/).
We downloaded our car dataset from [Hugging Face](https://huggingface.co/datasets/l-lt/LaSOT/tree/main).


## Project Requirements
### Pre-processing of Data:
- Extract Frames: Extract individual frames from the LaSOT video sequences (car category).
- Normalize and Resize: Normalize lighting conditions, resize the images, and apply Gaussian blur to reduce noise.

### Manual Feature Extraction (HOG):
- Use Histogram of Oriented Gradients (HOG) to extract features from video frames.
- Organize the extracted HOG feature vectors in csv file.





