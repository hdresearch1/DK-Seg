# Dense Visual Descriptions for Segmentation Benchmarks

This repository provides **structured textual descriptions** (dense semantic knowledge) for each category in four widely used image segmentation benchmarks:

- [COIFT](https://github.com/hdresearch1/DK-Seg)
- [DIS5K](https://github.com/hdresearch1/DK-Seg)
- [ThinObject-5K](https://github.com/hdresearch1/DK-Seg)
- [MS-COCO](https://cocodataset.org/)

These descriptions are designed to support **multimodal learning**, especially in tasks involving **vision-language segmentation**, **semantic grounding**, **zero-shot segmentation**, and **knowledge-enhanced encoder training**.

## 📂 Dataset Structure

├── COIFT_descriptions
├── DIS5K_descriptions
├── ThinObject5K_descriptions
├── COCO_descriptions

Descriptions were generated using large language models (e.g., GPT-4o) with prompt templates like:

“What is the visual appearance of a {class_name} in an image?”

## 🧠 Use Cases
This dataset can be used for:

Vision-language segmentation model training

Text-guided attention fusion or conditioning

Visual grounding tasks

Prompt generation for foundation models (e.g., SAM, CLIP, LLaVA)

Semantic enrichment of encoder layers (e.g., DK-Seg)

## 📜 License
This dataset is released under the CC BY 4.0 License.
Please cite our associated paper if you use it in your research.
