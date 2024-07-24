# [The WasteMS Dataset for Semantic Segmentation of Lakeside Waste](https://arxiv.org/abs/)

This is the official code repository for "Enhancing Environmental Monitoring through Multispectral Imaging: The WasteMS Dataset for Semantic Segmentation of Lakeside Waste". {[Arxiv Paper](https://arxiv.org/)}

![image](https://github.com/user-attachments/assets/07390b5e-49b5-4ac9-a3b5-3170ad62b2d4)

Fig. 1. Example images from the WasteMS dataset. (a) and (d) show the 9-channel data of two scenes; (b) and (e) are the ground truth mask; (c) and (f) are pseudo-color images composed using 9 channels.

[![GitHub stars](https://badgen.net/github/stars/zhuqinfeng1999/WasteMS)](https://github.com//zhuqinfeng1999/WasteMS)
[![arXiv](https://img.shields.io/badge/arXiv--b31b1b.svg)](https://arxiv.org/abs/)

## Abstract

Environmental monitoring of lakeside green areas is crucial for environmental protection. Compared to manual inspections, computer vision technologies offer a more efficient solution when deployed on-site. Multispectral imaging provides diverse information about objects under different spectrums, aiding in the differentiation between waste and lakeside lawn environments. This study introduces WasteMS, the first multispectral dataset established for the semantic segmentation of lakeside waste. WasteMS includes a diverse range of waste types in lawn environments, captured under various lighting conditions. We implemented a rigorous annotation process to label waste in images. Representative semantic segmentation frameworks were used to evaluate segmentation accuracy using WasteMS. Challenges encountered when using WasteMS for segmenting waste on lakeside lawns were discussed. The WasteMS dataset is available at https://github.com/zhuqinfeng1999/WasteMS.

## Download

The dataset is available at [Google Drive](https://drive.google.com/file/d/19Qi8qLsmPCAhX_rdKYtySOBAtjgeH3F_/view?usp=sharing).

## Dataset

The format of the WasteMS dataset is based on the mmsegmentation.

- ann_dir
  - train
    - .png
  - val
    - .png
  - test
    - .png
- img_dir
  - train
    - .tif
  - val
    - .tif
  - test
    - .tif

## Citation

If you find this work useful in your research, please consider cite:

```
@article{zhu2024,
  title={},
  author={},
  journal={},
  year={2024}
}


```
