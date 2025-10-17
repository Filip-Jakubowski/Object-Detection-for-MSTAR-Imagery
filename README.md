# Object Detection on MSTAR SAR Imagery (YOLOv8)

How easy is it to train apply object classification for the MSTAR IU Mixed Targets dataset using YOLOv8?

##  Dataset
- **MSTAR IU Mixed Targets** provided by the Sensor Data Management System.
- Contains SAR images of military vehicles under varying conditions.

##  Objectives
- Detect and localize military vehicles in SAR images.
- Adapt detection techniques to noisy, radar-specific data.

##  Methodology
1. Data preprocessing (resizing, normalization, augmentation).
2. Training YOLOv8 model with custom annotations (via Roboflow).
3. Evaluation using precision, recall, mAP.
4. Fine-tuning and comparison with other detection frameworks.

##  Results
- mAP@0.5: **98.9%**
- Inference speed: ** 100 ms/image**


<p align="center"> <img src="results/mstr1.png" width="280"/> <img src="results/mstr2.png" width="280"/> <img src="results/mstr3.png" width="280"/> </p>


##  License & Ethics
- Dataset licensed under CC BY 4.0 (via Roboflow)
- Project used solely for academic purposes.
- All credits attributed to [Sensor Data Management System]([https://...](https://www.sdms.afrl.af.mil/index.php?collection=mstar&page=mixed)).

## 🔗 Dataset Link
- Roboflow project: [MSTAR Dataset](https://universe.roboflow.com/project-zhu5n/object-detection-for-mstar-imagery)


