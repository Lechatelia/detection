### my trained results


| Backbone | Dataset | Train | test | Train time (s/iter) | Inf time (fps) | box AP | Download   |
| :--------------------: | :---: | :-----: | :------: | :----: | :-----: | :----: | :------: |
|faster rcnn resnet50 fpn| COCO14 |   train  | val     |            |  35.7 / 53.6   | 34.10 | 
|faster rcnn resnet101 fpn| COCO14 | train   | val     |     |     |  36.70 | 
|Fcos resnet50| COCO14 | train   | val     |     |     |  34.10 | 
|Retinanet resnet50| COCO14 | train   | val     |     |     |  33.80 | imgs_per_gpu=2
|Retinanet resnet50| COCO14 | train   | val     |     |     |  33.20 | imgs_per_gpu=4
|faster rcnn resnet50 fpn|VOC    | train07+12|val07|         |      |      80.19|