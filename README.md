# Implementation of the paper "Influence-based Approaches for Tumor Classification in Noisy Brain MRI with Deep Learning and Vision-Language Models"

## Download Brain Tumor Detection dataset
Please go this site [Brain Tumor Dataset](https://tinyurl.com/isr-isp-iicl) to download the data and put it in the folder named brain_tumor_dataset.

## Python environment
To run the code, please first install python environment with the following packages:
- openai
- google-generativeai
- Pillow
- numpy
- scipy
- tqdm
- pickle
- h5py
- scikit-learn
- pytorch
- torchvision

## Run our influence-based methods:
- To run ISR, please open the notebook ISP.ipynb and run the code.
- To run ISP, please open the notebook ISP.ipynb and run the code.
- To run IICL, please open the notebook IICL.ipynb and run the code. The results in this notebook are indices of selected demonstration examples. Please use those indices as input in inference_gpt4o.ipynb or inference_gemini.ipynb for getting classification results.

## Acknowledgement
- This work was supported  in part by National Science Foundation under awards 1946391, the National Institute of General Medical Sciences of National Institutes of Health under award P20GM139768, and the Arkansas Integrative Metabolic Research Center at University of Arkansas.
- Part of the implement of inlfuence function is inspired by [pytorch_influence_functions](https://github.com/nimarb/pytorch_influence_functions).
