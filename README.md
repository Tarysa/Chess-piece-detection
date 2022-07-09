## <div align="center">Chess pieces classification</div>

Small application to classify different chess pieces from different representation (real images, drawing, ...) with a pretrained MobileNetV2.

## <div align="center">Real time chess pieces detection</div>
 
Real time object detection by using Yolov5 on real annotated chess pieces.

Yolo preprocessing can be seen on a notebook of the same name.

To train with 300 epochs

```bash
python yolov5-master/train.py --img 640 --batch 16 --epochs 300 --data chess.yaml --weights yolov5s.pt

Inference in a test video

```bash
python yolov5-master/detect.py --weights yolov5-master/runs/train/exp2/weights/best.pt --source Dataset/detection/test_videos/video2.mp4

### <div align="center">Results</div>
