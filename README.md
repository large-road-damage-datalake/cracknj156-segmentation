# CrackNJ156

## Overview

Segmentation packaging of CrackNJ156, a manually annotated high-resolution pavement crack dataset collected on the NUIST campus under varied materials, weather, seasons, and illumination conditions.

- Task: segmentation
- Images: 156
- Annotations: 47497
- Classes: 1 (crack)
- Annotation format: paired PNG masks

The dataset covers road pavements with asphalt, concrete, stone, and terrazzo materials, and includes varied weather, season, and lighting conditions.
The local raw copy uses numeric image filenames and original mask filenames; the package preparation step aligns image-mask pairs by sorted filename order and materializes matching basenames for the pipeline.


## Source Dataset

- Name: CrackNJ156
- Dataset DOI: 10.5281/zenodo.6526409
- Dataset URL: https://zenodo.org/records/6526409
- Paper: https://www.sciencedirect.com/science/article/pii/S1569843222000279

## Authors

- Zhengsen Xu
- Haiyan Guan
- Jian Kang
- Xiangda Lei
- Lingfei Ma
- Yongtao Yu
- Yiping Chen
- Jonathan Li

## License

No explicit dataset license was identified from the source record.

## Repository Links

- Package repo: https://github.com/large-road-damage-datalake/cracknj156-segmentation
- Source dataset: https://zenodo.org/records/6526409

## Package Contents

- METADATA.json
- stats/
- visualizations/
- ABSTRACT.md
- SUMMARY.md
- CITATION.bib
- CITATION.md
- DOWNLOAD.md
- LICENSE.md
