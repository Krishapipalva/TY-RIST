TY-RIST: Tactical YOLO Tricks for Infrared Small Target Detection
Built on YOLOv12n (Ultralytics) + TY-RIST modifications from the paper
Modifications implemented:

Stride reduction (s=2 → s=1 in first Conv)
NWD regression loss (replaces CIoU)
Higher-resolution C2 feature map + P2 detection head
Coordinate Attention (CA) blocks on P2 branch
Model trimming (P3/P4/P5 heads removed at inference)
Tested on synthetic random data for architecture verification.
