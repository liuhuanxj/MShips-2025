# MShips-2025
The complete MShips-2025 dataset (approximately 5GB) is available for download via https://www.kaggle.com/datasets/njustliuhuan/mships-2025v1-0.
Note: This dataset is intended for academic research only. Please read and comply with the license terms below.

Overview
The MShips-2025 dataset is a publicly available, visible-light image collection specifically designed for the detection and recognition of military vessels and their critical onboard components (small targets). It addresses the lack of dedicated benchmarks in this domain and supports research in precise guidance systems for anti-ship equipment. The dataset simulates real-world maritime battlefield environments from a low-altitude perspective, encompassing various challenging conditions to enhance model robustness.

Dataset Details
Total Images: 3,729
Training Images: 2800
Validation Images: 464
Test Images:465
Total Instances (Bounding Boxes): 21,610
Image Resolution: Variable (annotated for input size 640×640)

Target Categories & Statistics
The dataset includes annotations for 3 main ship types and 4 key onboard component types.

Annotation Standard & Procedure
Annotation Format: YOLO format (.txt files, one per image).

Bounding Box: Axis-aligned rectangles.

Class IDs:

0: destroyer
1: submarine
2: aircraft_carrier
3: radar
4: battery
5: conning_tower
6: island
(Please verify this ID mapping matches your final annotation files.)

You are free to:

Share — copy and redistribute the material in any medium or format.
Adapt — remix, transform, and build upon the material.
Under the following terms:
Attribution — You must give appropriate credit, provide a link to the license, and indicate if changes were made.
NonCommercial — You may not use the material for commercial purposes.
No additional restrictions — You may not apply legal terms or technological measures that legally restrict others from doing anything the license permits.

Citation
If you use the MShips-2025 dataset in your research, please cite the associated paper:
And if you have any questions, please feel free to contact liuhuan@njust.edu.cn
