Requirements:
pytorch 1.0+
mmcv 0.4.0
cudatoolkit 10.1

Test 1-bit Faster-RCNN with ResNet-18 backbone achieved by LWS-Det:
tool/dist_test.sh faster_r18.py binarized_faster18.pth 1 --eval mAP

binarized_faster18.pth can be fetched in https://drive.google.com/file/d/1VoMTFZlNjqtUPjgwa1Fp5c6jcDEGbb8c/view?usp=sharing.
