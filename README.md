
## Files and Directories

- `IDC409_Group_04.ipynb`: Jupyter notebook containing the main code for the project.
- `lpr.v1i.yolov8/`: Directory containing the dataset and related files.
  - `data.yaml`: Configuration file for the dataset.
  - `README.dataset.txt`: Information about the dataset.
  - `README.roboflow.txt`: Information about the dataset from Roboflow.
  - `test/`: Directory containing test images and labels.
    - `cropped/`: Directory containing cropped test images.
    - `images/`: Directory containing test images.
    - `labels/`: Directory containing test labels.
  - `train/`: Directory containing training images and labels.
    - `images/`: Directory containing training images.
    - `labels/`: Directory containing training labels.
  - `valid/`: Directory containing validation images and labels.
    - `images/`: Directory containing validation images.
    - `labels/`: Directory containing validation labels.

## Getting Started

1. Clone the repository.
2. Install the required dependencies.
3. Run the Jupyter notebook `IDC409_Group_04.ipynb` to train and test the model.

## Dependencies

- Python 3.x
- Jupyter Notebook
- YOLOv8
- Other dependencies as listed in the notebook

## Usage

1. Prepare the dataset as described in the `data.yaml` file.
2. Run the Jupyter notebook to train the model.
3. Use the trained model to recognize license plates in test images.

## License

This project is licensed under the MIT License.