BASIC INFORMATION



Here:
any file with name or accrediation
exp_6 means VGG19 based data
exp_7 means MOBILENETv2  based data
exp_8 means EFFICIENTNETv2_s   based data




FILES ARE MOSTLY DIVIDED into
1. BASELINE (REPRODUCTION RESULTS AMD REDEVELOPMENT RESULTS)
2. OUR METHOD (EXTENSION RESULTS)






In FINAL DEEPROB PROJECT ----> Kitti_datasets_and_results ----> training (u will need 3 files)  -----> calib
                                                                                                ----> label_2
                                                                                                ----> image_2


and the same for  

FINAL DEEPROB PROJECT ----> Kitti_datasets_and_results ----> validation (u will need 3 files)  -----> calib
                                                                                                ----> label_2
                                                                                                ----> image_2



HERE WE DON'T HAVE OFFCIAL LABELS OF KITTI TEST DATSET FROM KITTI 3D OBEJCT DETECTION BENCHMARK, WE SPLIT OUR TRAIN DATASET INTO 5992 DATAPOINTS (TRAIN) AND 1488 (VALIDATION) i.e. APPROX 80:20 SPLIT
THE TRAIN DATASET CAN BE DOWNLOADED FROM HERE: https://www.cvlibs.net/datasets/kitti/eval_object.php?obj_benchmark=3d



In FINAL DEEPROB PROJECT ----> Kitti_datasets_and_results ----> training/validation -----> pred_images ----> BASELINE_images/OUR METHOD_images -----> exp6/exp7/exp8 -----> {each image is divided into 3 sections, the top section is 2D YOLO output,; the middle section is Ground truth 3D Bounding box
and the third section has our predictions for 3D Bounding box predictions} and for logistic convinence we have uploaded limited number of images in results, possibly covering all 3 classes.