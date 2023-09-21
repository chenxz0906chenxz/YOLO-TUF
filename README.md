# YOLO-TUF

Install
Clone repo and install requirements.txt in a Python>=3.8.0 environment, including PyTorch>=1.8.

git clone https://github.com/chenxz0906chenxz/YOLO-TUF

cd YOLO-TUF

pip install -r requirements.txt  

Training
The commands below reproduce YOLOv5 PSCAL VOC results. datasets download automatically from the latest YOLO-TUF release. Training times for YOLO-TUF is 3 days on a A100 GPU (Multi-GPU times faster).

python train.py

Inference

python detect.py --weights "Weight file path"
