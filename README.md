<H1 align="center">
Object-Counting-Blurring-YOLOV8 </H1>

## YOLOv8 Segmentation with DeepSORT Object Tracking

[`Github Repo Link`](https://github.com/kemaltekbas/Object-Counting-Blurring-YOLOV8.git)

## Steps to run Code

- Clone the repository
```
git clone https://github.com/kemaltekbas/Object-Counting-Blurring-YOLOV8.git
```
- Go to the cloned folder.
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

