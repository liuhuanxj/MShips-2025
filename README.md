# MShips-2025
The complete MShips-2025 dataset (approximately 5GB) is available for download via GitHub Releases.
Note: This dataset is intended for academic research only. Please read and comply with the license terms below.

Overview
The MShips-2025 dataset is a publicly available, visible-light image collection specifically designed for the detection and recognition of military vessels and their critical onboard components (small targets). It addresses the lack of dedicated benchmarks in this domain and supports research in precise guidance systems for anti-ship equipment. The dataset simulates real-world maritime battlefield environments from a low-altitude perspective, encompassing various challenging conditions to enhance model robustness.

Dataset Details
Total Images: 3,729
Training Images: 3,264
Validation Images: 465
Total Instances (Bounding Boxes): 21,610
Image Resolution: Variable (annotated for input size 640×640)

Target Categories & Statistics
The dataset includes annotations for 3 main ship types and 4 key onboard component types.

Class Distribution:

Destroyer: 1,743 instances (train), plus validation instances
Submarine: 1,288 instances (train), plus validation instances
Aircraft Carrier: 1,349 instances (train), plus validation instances
Radar: 12,455 instances (train), plus validation instances
Turret: 2,130 instances (train), plus validation instances
Conning Tower: 1,284 instances (train), plus validation instances
Island: 1,361 instances (train), plus validation instances
Total instances: 21,610 (19,888 train + 2,722 validation)

Target Size Distribution (relative to 640×640 input)
Size Category	Pixel Range	Train Instances	Val Instances
Small	area < 32×32	12,382	1,568
Medium	32×32 ≤ area ≤ 96×96	695	118
Large	area > 96×96	5,991	856
Data Source & Collection Methodology
Images were collected through web crawling from publicly available maritime databases, defense media, and video platforms. The collection aimed to simulate realistic operational scenarios for anti-ship equipment, covering a diverse range of conditions:

Multi-target scenes

Fog-occluded scenes

Long-distance views

Night-time scenes

Annotation Standard & Procedure
Annotation Format: YOLO format (.txt files, one per image).

Bounding Box: Axis-aligned rectangles.

Class IDs:

text
0: destroyer
1: submarine
2: aircraft_carrier
3: radar
4: turret
5: conning_tower
6: island
(Please verify this ID mapping matches your final annotation files.)

Quality Control: A two-stage manual verification process was employed:

Initial annotation by trained labelers.
Review and correction by domain experts to ensure accuracy, especially for small and occluded targets.
File Structure
The extracted dataset archive has the following structure:


path: /path/to/MShips-2025  # dataset root dir
train: images/train  # train images (relative to 'path')
val: images/val    # val images (relative to 'path')

# Class names
names:
  0: destroyer
  1: submarine
  2: aircraft_carrier
  3: radar
  4: turret
  5: conning_tower
  6: island
License
This dataset is released under the Creative Commons Attribution-NonCommercial 4.0 International (CC BY-NC 4.0) license.

You are free to:

Share — copy and redistribute the material in any medium or format.
Adapt — remix, transform, and build upon the material.
Under the following terms:
Attribution — You must give appropriate credit, provide a link to the license, and indicate if changes were made.
NonCommercial — You may not use the material for commercial purposes.
No additional restrictions — You may not apply legal terms or technological measures that legally restrict others from doing anything the license permits.
Full license text: https://creativecommons.org/licenses/by-nc/4.0/legalcode

Citation
If you use the MShips-2025 dataset in your research, please cite the associated paper:
