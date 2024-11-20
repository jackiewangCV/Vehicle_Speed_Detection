[![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1LsMQRXMKSvoYOkSkia0CwEa5j7TdQWPw?usp=sharing)

# Speed Estimation from Video using YOLOv9 and DeepSORT

This project estimates the speed of objects in a video using YOLOv9 for object detection and DeepSORT for tracking. The estimated speeds are overlaid on the video along with bounding boxes around the detected objects.

## Installation

1. Create new environment:
  - Using Conda
  ```bash
  conda env create -f conda.yml
  conda activate speed_py311
  ```

2. Install YOLOv9 dependency:
  ```bash
   pip install -r yolov9/requirements.txt
  ```
3. Download model weights:
   Download model weight from [here](https://drive.google.com/file/d/1rkL2VKMtpFAKVBnmXSwNq1yFlfY9KJ8k/view?usp=sharing)
  ```bash
   mkdir weights
   mv yolov9-e.pt weights
  ```
4. Download input video:
   Download video files from [here](https://drive.google.com/file/d/1-XNI75YQsJpEf-4KiIEiNJgp81CuBRgq/view?usp=sharing)
  ```bash
   mkdir content
   mv highway.mp4 content
  ```  
5. Run:
  ```bash
   python object_tracking.py
  ```
- To improve or customize model, please contact me. </br>
  `Email:` jackiewang13571@gmail.com</br>
  `Telegram:` [Click here](https://t.me/AIdevstar)</br>
  `WhatsApp:` [Click here](https://wa.me/+15095539271)</br>
  `Skype:` [Click here](https://join.skype.com/invite/epLIkMFiFRvQ)</br>
  `Portfolio:` [Click here](https://jackiewang13571.wixsite.com/jackie-wang)</br>
