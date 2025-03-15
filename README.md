# Brain Tumor Detection using YOLOv10

This project demonstrates how to use the YOLOv10 object detection model to detect brain tumors in medical images. It leverages the Ultralytics YOLO library for model training and inference, and Gradio for creating an interactive user interface.

## Requirements

To run this project, you'll need the following libraries:

* gradio
* ultralytics
* opencv-python
* roboflow
* matplotlib

You can install them using pip:

`bash pip install gradio ultralytics opencv-python roboflow matplotlib`

## Usage

1. **Download the Notebook:** Clone this repository to your local machine or download the notebook file directly.
2. **Open in Google Colab:** Open the notebook in Google Colab or a compatible Jupyter environment.
3. **Run the Cells:** Execute the code cells in the notebook sequentially.
   * The initial cells will install dependencies, download the YOLOv10 model, and prepare the dataset.
   * The training cell will fine-tune the model on the brain tumor dataset.
   * The inference cell will demonstrate how to make predictions on new images.
4. **Interact with the Gradio Interface:** The final cell will launch a Gradio interface where you can upload an image and visualize the tumor detections with confidence scores.

## Dataset

This project employs a brain tumor dataset hosted on Roboflow Universe. The dataset is sourced from the [MRI-RSKCU project](https://universe.roboflow.com/brain-mri/mri-rskcu) and consists of annotated brain MRI images.

## Model

This project utilizes the YOLOv10 object detection model, specifically the `yolov10n` variant. You can find detailed information about this model, including its architecture and performance comparisons, in the [Ultralytics documentation](https://docs.ultralytics.com/models/yolov10/#comparisons).