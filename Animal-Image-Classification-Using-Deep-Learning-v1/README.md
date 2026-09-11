# Animal Image Classification

A deep learning project for multi-class animal image classification using transfer learning and fine-tuning.

## Project Overview
The project is organized into three phases covering dataset preparation, baseline modeling, and transfer-learning experiments.

### Phase 1 — Dataset Preparation & Baselines
- Stratified 5-fold dataset splitting
- Initial model experiments
- Phase 1 report

### Phase 2 — GoogLeNet
- Frozen feature extractor
- Full fine-tuning
- Partial fine-tuning
- Comparative analysis

### Phase 3 — InceptionV3 & ResNet50
- Frozen feature extractor
- Full fine-tuning
- Partial fine-tuning
- Comparative analysis

## Repository Structure
```text
notebooks/   Training and preprocessing notebooks
reports/     Project reports
data/        Dataset documentation; large images are not stored here
results/     Metrics, plots, and evaluation outputs
src/         Reusable source code
models/      Model documentation/checkpoints (large checkpoints excluded)
```

## Dataset
The image dataset is stored separately on Google Drive because of its size. The repository contains the code and documentation needed to work with the dataset.

> Replace this line with the final Google Drive dataset link if you want to publish it.

## Reproducibility
Install the required Python packages using `requirements.txt`, then run the notebooks in phase order.

## Models
- GoogLeNet
- InceptionV3
- ResNet50

## Evaluation
Experiments should be compared using the metrics reported in the project notebooks/reports, such as accuracy, precision, recall, and F1-score.

## Notes
Large datasets, generated checkpoints, and other binary artifacts should not be committed directly to the repository.
