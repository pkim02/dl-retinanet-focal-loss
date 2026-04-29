# RetinaNet and Focal Loss for Object Detection

Portfolio project by `@pkim02`.

## Project Goal

An object detection project implementing RetinaNet components and focal loss training behavior in PyTorch.

## Notebooks

- `retinanet_focal_loss.ipynb`: RetinaNet and Focal Loss for Object Detection

## What I Implemented

- ResNet-style backbone usage for feature extraction.
- RetinaNet-style classification and box regression heads.
- Focal loss motivation and implementation for class imbalance.
- Training and test-time detection evaluation with final result discussion.

## Results

The notebook preserves training/test outputs and the final discussion about loss trends, detection accuracy, and overfitting behavior.

The notebooks keep most executed outputs so reviewers can inspect the results directly on GitHub. Full reproduction may require downloading the referenced public datasets or pretrained weights.

## How To Run

```bash
python -m venv .venv
.venv\Scripts\activate
pip install -r requirements.txt
jupyter notebook
```

Open the notebook listed above and run cells in order. GPU is optional for review, but recommended for rerunning training-heavy experiments.

## Citations

- Focal Loss for Dense Object Detection: https://arxiv.org/abs/1708.02002
- Torchvision detection references: https://pytorch.org/vision/stable/models.html
- PASCAL VOC dataset: http://host.robots.ox.ac.uk/pascal/VOC/

## Copyright And Data Note

This repository contains a cleaned portfolio version of my own implementation work. Assignment prompts, submission metadata, personal identifiers, and course-provided local figures were removed. The MIT license applies only to the code and documentation in this repository. Papers, datasets, pretrained weights, and any third-party libraries or assets keep their original licenses and terms.
