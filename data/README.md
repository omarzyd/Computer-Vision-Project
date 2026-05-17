# Data files

Place the following files in this directory before running the notebook:

| File | Description |
|------|-------------|
| `brand_of_can_soda.yolov8.zip` | YOLOv8 dataset export ([Roboflow — Brand of Can Soda](https://universe.roboflow.com/)) |
| `input_video.mp4` | Gameplay clip used for detection and fall tracking |

The notebook remaps all brand labels to a single `can` class for shelf detection.

**Colab:** upload both files to `/content/data/` (create the folder if needed).

**Local:** clone the repo and copy files here; paths resolve automatically from `notebooks/tin_can_fall_detection.ipynb`.

Large assets are listed in `.gitignore` and are not stored in Git. Keep your own copies for reproducibility.
