# Tzuku MadTec Automatic Annotation Example

## Example Video
The file `Tonalli_juguete-propio_cam-A_DLC.mp4` showcases the result s of automatic keypoint labeling done through Deep Lab Cut framework, and leveraging transfer learning from SuperAnimal Quadruped model.

> [!IMPORTANT]  
> The full dataset is **private** and subject to institutional data usage agreements. Access requests should be directed to hussein@cicese.mx.

---

## Feature Vector Header
This repository also includes the header from the generated feature vector ( see [`visual_feat_vector_header.csv`](visual_feat_vector_header.csv)), it comprises all the annotations made for every labeled frame, showing coordinates for each bodypart keyppint within the image, noramlized coordinates taken from object bounding boxes, and labels for activities and physionomic landmarks per each instance:

| video_id          | frame_filename | frame | Act level | Act type    | Act Tail Feature | ... | x_back_right_paw | y_back_right_paw | xmin    | ymin    | xmax    | ymax    |
|-------------------|----------------|-------|-----------|-------------|------------------|-----|------------------|------------------|---------|---------|---------|---------|
| Akira_ovalo_cam-B | img0643.png    | 643   | A1 Low    | A1 Lying    | H2 Tail-Down     | ... | nan              | nan              | 1195.48 | 652.293 | 1625.05 | 944.019 |
| Akira_ovalo_cam-B | img0715.png    | 715   | A1 Low    | A1 Lying    | H2 Tail-Down     | ... | nan              | nan              | 1102.35 | 702.564 | 1472.28 | 952.316 |
| Akira_ovalo_cam-B | img0759.png    | 759   | A1 Low    | A1 Lying    | H2 Tail-Down     | ... | nan              | nan              | 1161.69 | 657.94  | 1368.32 | 794.915 |
| Akira_ovalo_cam-B | img0890.png    | 890   | A1 Low    | A1 Lying    | H2 Tail-Down     | ... | nan              | nan              | 1026.59 | 702.041 | 1285.22 | 866.674 |
| Akira_ovalo_cam-B | img0930.png    | 930   | A1 Low    | A1 Lying    | H2 Tail-Down     | ... | nan              | nan              | 1071.96 | 784.128 | 1438.4  | 988.479 |
| Akira_ovalo_cam-B | img0995.png    | 995   | A1 Low    | A1 Lying    | H2 Tail-Down     | ... | nan              | nan              | 1062.78 | 801.337 | 1444.78 | 1003.16 |
| Akira_ovalo_cam-B | img1124.png    | 1124  | A1 Low    | A1 Lying    | H2 Tail-Down     | ... | nan              | nan              | 1012.76 | 804.106 | 1393.13 | 1005.16 |
| Akira_ovalo_cam-B | img1228.png    | 1228  | A1 Low    | A1 Lying    | H2 Tail-Down     | ... | nan              | nan              | 963.736 | 587.17  | 1394.74 | 1005    |
| Akira_ovalo_cam-B | img1346.png    | 1346  | A1 Low    | A1 Standing | H2 Tail-Down     | ... | 1192.27          | 966.734          | 858.177 | 644.313 | 1373.34 | 1013.67 |
| Akira_ovalo_cam-B | img1402.png    | 1402  | A1 Low    | A1 Standing | H2 Tail-Down     | ... | 1190.87          | 966.631          | 915.664 | 607.29  | 1353.85 | 1014.63 |
| Akira_ovalo_cam-B | img1619.png    | 1619  | A1 Low    | A1 Standing | H2 Tail-Down     | ... | 1218.26          | 969.528          | 880.48  | 620.306 | 1441.84 | 1014.51 |
| Akira_ovalo_cam-B | img1785.png    | 1785  | A1 Low    | A1 Standing | H2 Tail-Down     | ... | 1098.44          | 971.003          | 664.187 | 631.579 | 1235.05 | 999.559 |
| ...               | ...            | ...   | ...       | ...         | ...              | ... | ...              | ...              | ...     | ...     | ...     | ...     |      

--- 

## Licensing

### 1. Media & Data License (All Rights Reserved)

The example video (`Tonalli_juguete-propio_cam-A_DLC.mp4`) and any provided sample weights are **proprietary assets** and are **not** licensed for public reuse, modification, or redistribution (see [LICENSE_MEDIA](LICENSE_MEDIA.txt)). 

**Copyright © 2026 CICESE. All Rights Reserved.**

**Under this restrictive notice:**

* **No Redistribution:** You may **not** copy, share, or host this video.
* **No Modification:** You may **not** edit, remix, or create derivative works from these assets.
* **Non-Commercial:** Commercial use of these assets is strictly prohibited.
* **Institutional Property:** These assets are derived from a private dataset developed by **CICESE** and are subject to institutional data privacy agreements.

[![License: All Rights Reserved](https://img.shields.io/badge/License-All_Rights_Reserved-red.svg)](https://en.wikipedia.org/wiki/All_rights_reserved)
