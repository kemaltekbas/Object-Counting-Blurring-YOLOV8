<H1 align="center">
Object-Counting-Bluring-YOLOV8 </H1>

## Google Colab File Link (A Single Click Solution)
The google colab file link for yolov8 object tracking, blurring and  counting is provided below, you can check the implementation in Google Colab, and its a single click implementation
,you just need to select the Run Time as GPU, and click on Run All.

[`Google Colab File`](https://colab.research.google.com/drive/1haDui8z7OvITbOpGL1d0NFf6M4BxcI-y?usp=sharing)

## YOLOv8 Segmentation with DeepSORT Object Tracking

[`Github Repo Link`](https://github.com/kemaltekbas/Object-Counting-Blurring-YOLOV8.git)

## Steps to run Code

- Clone the repository
```
git clone https://github.com/kemaltekbas/Object-Counting-Blurring-YOLOV8.git
```
- Goto the cloned folder.
```
cd Object-Counting-Blurring-YOLOV8
```
- Install the dependecies
```
pip install -e .
pip install -e '.[dev]'

This way you install the main project as editable (-e) and then install the development dependencies. You can run the commands by following these two steps.
```

- Setting the Directory.
```
cd ultralytics/yolo/v8/detect

```
- Downloading the DeepSORT Files From The Google Drive 
```

https://drive.google.com/drive/folders/1kna8eWGrSfzaR6DtNJ8_GchGgPMv3VC8?usp=sharing
```
- After downloading the DeepSORT Zip file from the drive, unzip it go into the subfolders and place the deep_sort_pytorch folder into the yolo/v8/detect folder

- Run the code with mentioned command below.

- For yolov8 object detection, Tracking,  blurring and object counting
```
python predict.py model=yolov8s.pt source="video.mp4" show=True
```

