# OTMJ

The OTMJ (Object Detection in Mountain Jungle) dataset is an RGB dataset used for object tracking in mountainous jungle scenes.

## News

**[August 7, 2024]**
We have open-source the OTMJ dataset, which now includes 24 drone target tracking sequences in mountainous and jungle scenes. Additionally, you can view the comparison of our TrackingMamba with advanced trackers on the current OTMJ dataset at [[TrackingMamba](https://github.com/KustTeamWQW/TrackingMamba)]

## Introduction

​    ![Yunnan topographic map](E:\Users\Desktop\Yunnan topographic map.png)

​                                                                                Fig.1.  Yunnan topographic map.

The OTMJ dataset was captured by us using drones in various mountain forest areas along the borders and suburban mountainous regions of Yunnan, China, covering multiple angles. As shown in Fig.1, Yunnan's terrain is complex, with mountainous areas accounting for the vast majority of the total area, and mountain forests are widely distributed. Comparing Kunming and Xishuangbanna in Yunnan, the terrain around Kunming is mainly hilly, with elevations mostly around 2000 meters. The vegetation is primarily subtropical evergreen broadleaf forests, accompanied by coniferous forests. In contrast, Xishuangbanna has undulating mountains and deep ravines with significant elevation differences. The vegetation is mainly tropical rainforests, with an extremely rich variety of plant species. Additionally, Yunnan has a long border, and the areas near the border are mostly mountainous forests. 

These factors have prompted us to conduct research on drone target tracking in the mountain forest scenes of Yunnan, leading to the creation of this dataset. It covers multiple angles and currently includes multiple sequences, each with detailed object bounding box annotations. The image resolution is 640 × 512.
We meticulously screened and preprocessed these sequences to avoid high repetition from intermittent shooting at the same location, prevent external factors that could enhance object features from continuous sampling, and applied frame skipping to some sequences to assess tracker performance under extreme conditions. 

Compared to traditional datasets, this dataset features a wide range of challenging situations such as object occlusion, disappearance, camera shake, large-scale changes in object size, and low light. To more realistically simulate special conditions encountered in the jungle, we applied military camouflage to objects in some sequences. 

This dataset is continuously being organized and expanded with the aim of advancing the field of drone target tracking in mountainous forest areas in the future.



## Obtain Dataset

The dataset can be accessed through this link:  [[Baidu Netdisk](https://pan.baidu.com/s/19WDZJ3b0-OPBrOi72n8eXg?pwd=ee9z)], Extract code: ee9z.

