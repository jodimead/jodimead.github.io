---
title: "Advancing Snow Depth Monitoring with Machine Learning and L-band InSAR Data: A Case Study Using SnowEx 2017 Data"
collection: publications
permalink: /publication/2024-8-01-Advancing-Snow-Depth-Monitoring-with-Machine-Learning-and-L-band-InSAR-Data-A-Case-Study-Using-SnowEx-2017-Data
date: 2024-08-01
venue: Frontier in Remote Sensing, Sec. Microwave Remote Sensing, Volume 5, 2024
---

Download [here](https://jodimead.github.io/files/papers/alabi_et_al.pdf)

Abstract: 
Current snow depth mapping from space faces challenges in spatial coverage, revisit frequency, and cost. Airborne lidar, although precise, incurs high costs and has limited geographical coverage, thereby necessitating the exploration of alternative, cost-effective methodologies for snow depth estimation.  The forthcoming NASA-ISRO Synthetic Aperture Radar (NISAR) mission, with its 12-day global revisit cycle and 1.25 GHz L-band frequency, introduces a promising avenue for cost-effective, large-scale snow depth and snow water equivalent (SWE) estimation using L-band Interferometric SAR (InSAR) capabilities. This study demonstrates InSAR's potential for snow depth estimation via machine learning. Using 3 m resolution L-band InSAR products over Grand Mesa, Colorado, we compared the performance of three machine learning approaches (XGBoost, ExtraTrees, and Neural Networks) across open, vegetated, and the combined (open + vegetated) datasets using Root Mean Square Error (RMSE), Mean Bias Error (MBE), and R² metrics. XGBoost emerged as the superior model, with RMSE values of 9.85 cm, 10.46 cm, and 9.88 cm for open, vegetated, and combined regions, respectively. Validation against in-situ snow depth measurements resulted in an RMSE of approximately 16 cm, similar to in-situ validation of the airborne lidar. Our findings indicate that L-band InSAR, with its ability to penetrate clouds and cover extensive areas, coupled with machine learning, holds promise for enhancing snow depth estimation. This approach, especially with the upcoming NISAR launch, may enable high-resolution (~10 m) snow depth mapping over extensive areas, provided suitable training data are available, offering a cost-effective approach for snow monitoring.  The code and data used in this work are available at https://github.com/cryogars/uavsar-lidar-ml-project.


Bibtex:<br>
@ARTICLE{10.3389/frsen.2024.1481848,
    
AUTHOR={Alabi, Ibrahim Olalekan  and Marshall, Hans-Peter  and Mead, Jodi  and Trujillo, Ernesto },
           
TITLE={Advancing terrestrial snow depth monitoring with machine learning and L-band InSAR data: a case study using NASA’s SnowEx 2017 data},
          
JOURNAL={Frontiers in Remote Sensing},
          
VOLUME={Volume 5 - 2024},
  
YEAR={2025},
  
URL={https://www.frontiersin.org/journals/remote-sensing/articles/10.3389/frsen.2024.1481848},
  
DOI={10.3389/frsen.2024.1481848},
  
ISSN={2673-6187}}
