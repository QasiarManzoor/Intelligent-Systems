# Instruction-Guided Inference for Image Captioning: A Reproducible CNN–Transformer Implementation

This repository contains a reproducible prototype implementation of an instruction-guided multimodal reasoning system using image–text data from the MS-COCO dataset.

## Project Overview
The project demonstrates instruction-following multimodal reasoning without full instruction-tuned retraining, emphasizing efficiency, transparency, and reproducibility for academic research.

## Key Objectives
- Instruction-guided image captioning and reasoning
- Parameter-efficient multimodal inference
- Public dataset usage (MS-COCO)
- Transparent and explainable outputs

## Methodology
The pipeline includes:
1. Visual feature extraction using pretrained encoders
2. Instruction-based text processing
3. Natural language output generation

## Repository Structure
- coco-model-qaisar.ipynb: Main implementation notebook
- README.md: Project documentation

## Dataset
MS-COCO (Microsoft Common Objects in Context)

## How to Run
Open the notebook and execute cells sequentially:
jupyter notebook coco-model-qaisar.ipynb

## Future Work
- LoRA / QLoRA integration
- Chain-of-Thought reasoning
- Extension to ScienceQA and VQAv2

## Author
Qaisar Manzoor
