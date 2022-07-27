# P2PNet with backbone from YOLOV6
 This model replaced Vgg16-bn and decoder in P2PNet with RepVGG and Rep-PAN.  However, the number of channels keeps decreasing in Rep-PAN, which may pose a negative effect when fusing different feature maps. And it doesn't perform as good as expected.
