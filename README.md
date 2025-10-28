# Sport-Pose-Isolation
This repo uses colab to make a subject isolation and background masking for sports video analysis. A demo for the processed on for mma and cricket have been uploaded in the repo. Used yolo v8 segmentation and pose model for keypoint detecetion and deepsort for tracking them. Used iou masking for clener segmentation, on overlapping objects.

Can serve as a backbone for sports based tracking

The keypoints were not stable and the pose matrices need to be more accurate.

Need to add more stable matrices for specific analysis in any sport. Angular metrices for better biomechanics analysis
