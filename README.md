# YOLO11 Custom Model Training on Roboflow Dataset

This repository contains four Jupyter Notebooks for training the YOLO11 model on custom datasets sourced from [Roboflow](https://roboflow.com/). The model is trained for different tasks including image classification, instance segmentation, object detection, and pose estimation. All code is developed and executed using Google Colab, with paths and dataset configuration appropriately set within the notebooks (check code comments).

## Files in the Repository

- **Image_Classification_YOLO11.ipynb**: Notebook for training YOLO11 for image classification.
- **Instance_Segmentation_YOLO11.ipynb**: Notebook for training YOLO11 for instance segmentation.
- **Object_Detection_YOLO11.ipynb**: Notebook for training YOLO11 for object detection tasks.
- **Pose_Detection_YOLO11.ipynb**: Notebook for training YOLO11 to detect and estimate human poses.
- **README.md**: This file.

## How to Use

1. **Clone the Repository**:
    ```bash
    git clone https://github.com/Raihan4520/YOLO11.git
    cd YOLO11
    ```

2. **Set Up Dependencies**:
   - Ensure that you have all the required dependencies installed. You can install them by running the cells in the notebook, which will handle the installation of necessary libraries (including `ultralytics` and `roboflow`).

3. **Obtain Roboflow Dataset**:
   - Create an account at [Roboflow](https://roboflow.com/) and upload your dataset. You may also use an existing dataset from `Roboflow Universe`.
   - Once your dataset is ready, retrieve the API key from Roboflow and replace it in the corresponding section of the notebook.

4. **Check and Update Paths**:
   - The file paths within the notebooks are set up for Google Colab. If you are using a different environment, update the paths to match your local file structure (check code comments).

5. **Run the Notebook**:
   - Open the notebook in Google Colab or your preferred environment and run each cell sequentially.
   - Ensure you have a stable internet connection, as the notebooks require fetching the dataset and model weights from external sources.

## Notes

- Each notebook is fully commented to guide you through the process of training YOLO11 on a custom dataset.
- If you are using a different dataset, make sure to modify the dataset paths and configuration settings as needed.
- The project is optimized for use with Google Colab, where paths and file structure are pre-configured.
- Check code comments properly.

## Dataset

- This project utilizes custom datasets from Roboflow. You can replace the dataset with your own by following the instructions in the notebook. Make sure to use your own dataset API key when running the cells.

## Tasks Covered

1. **Image Classification**: Assign a label to an image based on its contents.
2. **Instance Segmentation**: Segment different instances of objects within an image.
3. **Object Detection**: Detect objects and locate them with bounding boxes.
4. **Pose Detection**: Estimate the pose of humans in images, detecting keypoints such as joints.

## Acknowledgements

- [Ultralytics](https://github.com/ultralytics/ultralytics) for providing the YOLO11 model.
- [Roboflow](https://roboflow.com/) for the custom dataset API.

## YOLOv8 Comparison

Before working with YOLOv11, I previously trained the model using [YOLOv8](https://github.com/Raihan4520/YOLOv8) with the same dataset and settings. Feel free to check the YOLOv8 repository and compare the performance, results, and implementation between YOLOv8 and YOLOv11.

For more details on YOLOv8, visit the repository [here](https://github.com/Raihan4520/YOLOv8).

## Contact

If you have any questions or suggestions, feel free to reach out through the repository's issues or contact me directly.
