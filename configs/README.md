### my trained results


| Backbone | Dataset | Train | test | Train time (s/iter) | Inf time (fps) | box AP |                                                             Download                                                             |
| :--------------------: | :---: | :-----: | :------: | :----: | :-----: | :----: | :-------------------------------------------------------------: |
|faster rcnn resnet50 fpn| COCO14 |   train  | val     |            |  35.7 / 53.6   | 34.10 | [model](https://s3.ap-northeast-2.amazonaws.com/open-mmlab/mmdetection/models/ssd300_voc_vgg16_caffe_240e_20190501-7160d09a.pth) |
|faster rcnn resnet101 fpn| COCO14 | train   | val     |     |     |  36.70 | [model](https://s3.ap-northeast-2.amazonaws.com/open-mmlab/mmdetection/models/ssd512_voc_vgg16_caffe_240e_20190501-ff194be1.pth) |
|faster rcnn resnet50 fpn|VOC    | train07+12|val07|         |      |      80.19|