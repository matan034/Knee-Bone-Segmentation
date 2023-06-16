# Knee-Bone-Segmentation
Osteoarthritis (OA) occurs when cartilage cushions at the
ends of bones are lost, causing friction between the femur and the tibia.
Using the segmentation of the aforementioned bones, doctors will be able
to identify the onset of arthritis early and provide crucial information to
manufacturers of 3D-printed knees. In addition, total knee arthroplasty
(TKA) will provide a greater degree of accuracy. At present, no automatic
segmentation of these two bones is available or widely used. In order to
segment the bone knee, the challenge lies in developing a system that is
accurate enough to be used in clinical settings. In order to accomplish
this task, we conducted research on the U-net architecture - a common
deep learning model for segmentation - and determine which U-nets are
most appropriate for the given task. Furthermore, we proposed a novel
architecture that enhances Attention Unet which has Transfer learning
for the encoder in order to reduce the networks parameters. It has an
extra depth layer that extracts more features. Further more it has a Clas-
sifier unit that reduces the amount of false positives, and an innovative
loss function in the form of Trvesky loss. The proposed architecture was
evaluated by predicting a volumetric CT scan from Papa Giovanni hos-
pital, thus resulting in a complete 3D model of the femur which achieved
a higher dice coefficient score than our base model, Attention U net.

![image](https://github.com/matan034/Knee-Bone-Segmentation/assets/61933614/6b01df14-4638-4b52-b567-c1b11602be3c)

# Requirments
in order to use dataset you need to mount our google drive.
click link https://drive.google.com/drive/folders/1oy7S3qaF740F5nC6zCtktwvXTh2xAuug?usp=drive_link
1. Select "Shared with me" on side menu.
2. Locate the "KneeProject" folder and open menu.
3. Select "Add shortcut to Drive"
