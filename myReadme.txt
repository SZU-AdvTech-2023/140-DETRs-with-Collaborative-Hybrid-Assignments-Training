# 模型预测: python demo/image_demo.py demo/demo.jpg 
            projects/configs/co_deformable_detr/co_deformable_detr_r50_1x_coco.py 
            checkpoints/co_deformable_detr_r50_1x_coco.pth 
            --device cuda 
            --out-file output.png

# 模型训练: bash tools/dist_train.sh projects/configs/co_deformable_detr/co_deformable_detr_r50_1x_coco.py 1 path_to_exp

最好结果:
co_deformable_detr_r50_1x_uavrod：12pt

 Average Precision  (AP) @[ IoU=0.50:0.95 | area=   all | maxDets=100 ] = 0.815
 Average Precision  (AP) @[ IoU=0.50      | area=   all | maxDets=1000 ] = 0.978
 Average Precision  (AP) @[ IoU=0.75      | area=   all | maxDets=1000 ] = 0.845
 Average Precision  (AP) @[ IoU=0.50:0.95 | area= small | maxDets=1000 ] = -1.000
 Average Precision  (AP) @[ IoU=0.50:0.95 | area=medium | maxDets=1000 ] = 0.751
 Average Precision  (AP) @[ IoU=0.50:0.95 | area= large | maxDets=1000 ] = 0.848
 Average Recall     (AR) @[ IoU=0.50:0.95 | area=   all | maxDets=100 ] = 0.865
 Average Recall     (AR) @[ IoU=0.50:0.95 | area=   all | maxDets=300 ] = 0.865
 Average Recall     (AR) @[ IoU=0.50:0.95 | area=   all | maxDets=1000 ] = 0.865
 Average Recall     (AR) @[ IoU=0.50:0.95 | area= small | maxDets=1000 ] = -1.000
 Average Recall     (AR) @[ IoU=0.50:0.95 | area=medium | maxDets=1000 ] = 0.781
 Average Recall     (AR) @[ IoU=0.50:0.95 | area= large | maxDets=1000 ] = 0.905

2023-11-03 06:37:54,548 - mmdet - INFO - Exp name: co_deformable_detr_r50_1x_uavrod.py
2023-11-03 06:37:54,549 - mmdet - INFO - Epoch(val) [12][427]	bbox_mAP: 0.8150, bbox_mAP_50: 0.9780, bbox_mAP_75: 0.8450, bbox_mAP_s: -1.0000, bbox_mAP_m: 0.7510, bbox_mAP_l: 0.8480, bbox_mAP_copypaste: 0.815 0.978 0.845 -1.000 0.751 0.848


co_deformable_detr_r50_3x_uavrod：35pt

 Average Precision  (AP) @[ IoU=0.50:0.95 | area=   all | maxDets=100 ] = 0.818
 Average Precision  (AP) @[ IoU=0.50      | area=   all | maxDets=1000 ] = 0.979
 Average Precision  (AP) @[ IoU=0.75      | area=   all | maxDets=1000 ] = 0.847
 Average Precision  (AP) @[ IoU=0.50:0.95 | area= small | maxDets=1000 ] = -1.000
 Average Precision  (AP) @[ IoU=0.50:0.95 | area=medium | maxDets=1000 ] = 0.758
 Average Precision  (AP) @[ IoU=0.50:0.95 | area= large | maxDets=1000 ] = 0.850
 Average Recall     (AR) @[ IoU=0.50:0.95 | area=   all | maxDets=100 ] = 0.861
 Average Recall     (AR) @[ IoU=0.50:0.95 | area=   all | maxDets=300 ] = 0.861
 Average Recall     (AR) @[ IoU=0.50:0.95 | area=   all | maxDets=1000 ] = 0.861
 Average Recall     (AR) @[ IoU=0.50:0.95 | area= small | maxDets=1000 ] = -1.000
 Average Recall     (AR) @[ IoU=0.50:0.95 | area=medium | maxDets=1000 ] = 0.781
 Average Recall     (AR) @[ IoU=0.50:0.95 | area= large | maxDets=1000 ] = 0.899

2023-11-29 17:48:39,552 - mmdet - INFO - Exp name: co_deformable_detr_r50_3x_uavrod.py
2023-11-29 17:48:39,552 - mmdet - INFO - Epoch(val) [35][427]	bbox_mAP: 0.8180, bbox_mAP_50: 0.9790, bbox_mAP_75: 0.8470, bbox_mAP_s: -1.0000, bbox_mAP_m: 0.7580, bbox_mAP_l: 0.8500, bbox_mAP_copypaste: 0.818 0.979 0.847 -1.000 0.758 0.850

co_deformable_detr_swin_small_3x_uavrod：35pt

Average Precision  (AP) @[ IoU=0.50:0.95 | area=   all | maxDets=100 ] = 0.825
 Average Precision  (AP) @[ IoU=0.50      | area=   all | maxDets=1000 ] = 0.979
 Average Precision  (AP) @[ IoU=0.75      | area=   all | maxDets=1000 ] = 0.851
 Average Precision  (AP) @[ IoU=0.50:0.95 | area= small | maxDets=1000 ] = -1.000
 Average Precision  (AP) @[ IoU=0.50:0.95 | area=medium | maxDets=1000 ] = 0.763
 Average Precision  (AP) @[ IoU=0.50:0.95 | area= large | maxDets=1000 ] = 0.858
 Average Recall     (AR) @[ IoU=0.50:0.95 | area=   all | maxDets=100 ] = 0.864
 Average Recall     (AR) @[ IoU=0.50:0.95 | area=   all | maxDets=300 ] = 0.864
 Average Recall     (AR) @[ IoU=0.50:0.95 | area=   all | maxDets=1000 ] = 0.864
 Average Recall     (AR) @[ IoU=0.50:0.95 | area= smssall | maxDets=1000 ] = -1.000
 Average Recall     (AR) @[ IoU=0.50:0.95 | area=medium | maxDets=1000 ] = 0.783
 Average Recall     (AR) @[ IoU=0.50:0.95 | area= large | maxDets=1000 ] = 0.902

2023-11-30 19:30:06,863 - mmdet - INFO - Exp name: co_deformable_detr_swin_small_3x_uavrod.py
2023-11-30 19:30:06,863 - mmdet - INFO - Epoch(val) [35][427]	bbox_mAP: 0.8250, bbox_mAP_50: 0.9790, bbox_mAP_75: 0.8510, bbox_mAP_s: -1.0000, bbox_mAP_m: 0.7630, bbox_mAP_l: 0.8580, bbox_mAP_copypaste: 0.825 0.979 0.851 -1.000 0.763 0.858

co_deformable_detr_swin_tiny_3x_uavrod：35pt

 Average Precision  (AP) @[ IoU=0.50:0.95 | area=   all | maxDets=100 ] = 0.814
 Average Precision  (AP) @[ IoU=0.50      | area=   all | maxDets=1000 ] = 0.978
 Average Precision  (AP) @[ IoU=0.75      | area=   all | maxDets=1000 ] = 0.833
 Average Precision  (AP) @[ IoU=0.50:0.95 | area= small | maxDets=1000 ] = -1.000
 Average Precision  (AP) @[ IoU=0.50:0.95 | area=medium | maxDets=1000 ] = 0.754
 Average Precision  (AP) @[ IoU=0.50:0.95 | area= large | maxDets=1000 ] = 0.844
 Average Recall     (AR) @[ IoU=0.50:0.95 | area=   all | maxDets=100 ] = 0.867
 Average Recall     (AR) @[ IoU=0.50:0.95 | area=   all | maxDets=300 ] = 0.867
 Average Recall     (AR) @[ IoU=0.50:0.95 | area=   all | maxDets=1000 ] = 0.867
 Average Recall     (AR) @[ IoU=0.50:0.95 | area= small | maxDets=1000 ] = -1.000
 Average Recall     (AR) @[ IoU=0.50:0.95 | area=medium | maxDets=1000 ] = 0.784
 Average Recall     (AR) @[ IoU=0.50:0.95 | area= large | maxDets=1000 ] = 0.907

2023-11-30 07:05:01,521 - mmdet - INFO - Exp name: co_deformable_detr_swin_tiny_3x_uavrod.py
2023-11-30 07:05:01,521 - mmdet - INFO - Epoch(val) [35][427]	bbox_mAP: 0.8140, bbox_mAP_50: 0.9780, bbox_mAP_75: 0.8330, bbox_mAP_s: -1.0000, bbox_mAP_m: 0.7540, bbox_mAP_l: 0.8440, bbox_mAP_copypaste: 0.814 0.978 0.833 -1.000 0.754 0.844

co_dino_5scale_r50_3x_uavrod：49pt

 Average Precision  (AP) @[ IoU=0.50:0.95 | area=   all | maxDets=100 ] = 0.823
 Average Precision  (AP) @[ IoU=0.50      | area=   all | maxDets=1000 ] = 0.980
 Average Precision  (AP) @[ IoU=0.75      | area=   all | maxDets=1000 ] = 0.856
 Average Precision  (AP) @[ IoU=0.50:0.95 | area= small | maxDets=1000 ] = -1.000
 Average Precision  (AP) @[ IoU=0.50:0.95 | area=medium | maxDets=1000 ] = 0.759
 Average Precision  (AP) @[ IoU=0.50:0.95 | area= large | maxDets=1000 ] = 0.857
 Average Recall     (AR) @[ IoU=0.50:0.95 | area=   all | maxDets=100 ] = 0.855
 Average Recall     (AR) @[ IoU=0.50:0.95 | area=   all | maxDets=300 ] = 0.855
 Average Recall     (AR) @[ IoU=0.50:0.95 | area=   all | maxDets=1000 ] = 0.855
 Average Recall     (AR) @[ IoU=0.50:0.95 | area= small | maxDets=1000 ] = -1.000
 Average Recall     (AR) @[ IoU=0.50:0.95 | area=medium | maxDets=1000 ] = 0.775
 Average Recall     (AR) @[ IoU=0.50:0.95 | area= large | maxDets=1000 ] = 0.894

2023-12-02 13:27:12,145 - mmdet - INFO - Exp name: co_dino_5scale_r50_3x_uavrod.py
2023-12-02 13:27:12,145 - mmdet - INFO - Epoch(val) [49][427]	bbox_mAP: 0.8230, bbox_mAP_50: 0.9800, bbox_mAP_75: 0.8560, bbox_mAP_s: -1.0000, bbox_mAP_m: 0.7590, bbox_mAP_l: 0.8570, bbox_mAP_copypaste: 0.823 0.980 0.856 -1.000 0.759 0.857