To run Google drive:-
!python /content/drive/MyDrive/face_mask_yolov6/YOLOv6-main/YOLOv6-main/tools/infer.py   --weights /content/drive/MyDrive/face_mask_yolov6/YOLOv6-main/YOLOv6-main/runs/train/exp3/weights/best_ckpt.pt --source /content/drive/MyDrive/face_mask_yolov6/YOLOv6-main/YOLOv6-main/data/WIN_20230418_13_22_43_Pro.mp4

To open webcam in pc:-
python tools/infer.py --weights yolov6s.pt --webcam --webcam-addr 0


To run in pc:-
python E:\Work\face_mask_yolov6\YOLOv6-main\tools\infer.py   --weights E:\Work\face_mask_yolov6\YOLOv6-main\runs\train\100_epoch\best_ckpt.pt  --source E:\Work\face_mask_yolov6\YOLOv6-main\data\WIN_20230418_17_13_58_Pro.jpg


#Note:- source file will be changeable just copy paste data path of image or videos