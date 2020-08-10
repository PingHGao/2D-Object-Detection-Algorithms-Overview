| 模型 | APtest | AP50 | FPS | Params | FLOPS | Year |
|--|--|--|--|--|--|--|
| [YOLOV5s](https://github.com/ultralytics/yolov5) | 36.1(coco2017) | 55.3 | 476(V100) | 7.5M | 13.2B | 2020 |
| [YOLOV5m](https://github.com/ultralytics/yolov5) | 43.5(coco2017) | 62.5| 333(V100) | 21.8M | 39.4B | 2020 |
| [YOLOV5x](https://github.com/ultralytics/yolov5) | 49.0(coco2017) | 67.4| 164(V100) | 89.0M | 166.4B | 2020 |
| [YOLOV3-spp](https://github.com/ultralytics/yolov3) | 45.5(coco2017) | 65.2| 222(V100) | 63.0M | 118.0B | 2018 |
| [YOLOV3-spp](https://pjreddie.com/darknet/yolo/) | - | 60.6(coco) | 20(Titan X) | - | 141.45B | 2018 |
| [YOLOV3-416](https://pjreddie.com/darknet/yolo/) | - | 55.3(coco) | 35(Titan X) | - | 65.86B | 2018 |
| [YOLOV3-tiny](https://pjreddie.com/darknet/yolo/) | - | 33.1(coco) | 220(Titan X) | - | 5.56B | 2018 |
| [SSD300](https://pjreddie.com/darknet/yolo/) | - | 41.2(coco) | 46(Titan X) | -| - | 2016 |
| [SSD513](https://pjreddie.com/darknet/yolo/) | - | 50.4(coco) | 8(Titan X) | -| - | 2016 |
| [Retinanet-50-500](https://pjreddie.com/darknet/yolo/) | - | 50.9(coco) | 14(Titan X) | -| - | 2017 |
| [Retinanet-101-500](https://pjreddie.com/darknet/yolo/) | - | 53.1(coco) | 11(Titan X) | -| - | 2017 |
| Faster RCNN(VGG 16) | - | 42.7(coco) | 7(TitanX) | - | - | 2015 |

注：

 - **FLOPS：** 浮点运算次数，用来衡量模型的计算量的大小。
 - **Params：** 参数的数量。
 - **APtest**  对应 COCO test-dev2017 结果
