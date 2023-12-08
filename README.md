# Applying XAI to Heart Failure Prediction Model

## Project information
- **Author**: Yian Pei, Applied Math - Computer science, Class of 2025, Duke Kunshan University
- **Instructor**: Prof. Luyao Zhang, Duke Kunshan University
- **Disclaimer**: Submissions to the Final Project for [Econ211 Intelligent Economy, 2023 Autumn Term (Seven Week - Second)](https://ms.pubpub.org/) instructed by Prof. Luyao Zhang at Duke Kunshan University.
- **Acknowledgments**: I extend my deepest gratitude to Prof. Luyao Zhang, Yiwei Liang, Jiaolun Zhou, Zhe Niu, Enzo Rovira and Zakhar Merinov for their unwavering guidance, expertise, and encouragement, which helped me finish this project.

- **Project Summary**: 
  - This project aims to improve heart failure prediction by integrating Explainable Artificial Intelligence (XAI) techniques into a binary classification model. Focused on healthcare, the research utilizes machine learning algorithms and a diverse dataset to enhance transparency and interpretability. The outcomes are expected to yield a refined predictive model, fostering collaboration between healthcare professionals and AI. The intellectual merits lie in advancing healthcare AI, offering transparent and trustworthy models, while the practical impact empowers clinicians with a tool that predicts heart failure and provides understandable insights for improved patient outcomes.

    Research questions:
  - How can SHAP effectively define what clinicians should focus on when predicting heart failure?
  - Will the change of data input (Sex, Age) affect the integration of XAI?

## Table of Contents

1. [**Poster and Project Summary**](./Poster-and-Project-Summary)
2. [**Literature**](./Literature)
3. [**Method**](./Method)
4. [**Data**](./Data)
    - 4.1 [Queried-Data](./Data/Queried-Data)
    - 4.2 [Processed-Data](./Data/Processed-Data)
5. [**Code**](./Code)
    - 5.1 [Data-Analysis](./Code/Data-Analysis)
    - 5.2 [Data-Query](./Code/Data-Query)
6. [**Results**](./Results)
7. [**Spotlights**](./Spotlights)
8. **More about the Author**
9. **References**

## Literature
In this research, the literature review focuses on four key articles contributing to the study of parameter weight analysis using SALib. The first article provides an overview of SALib, outlining its significance in sensitivity analysis. The second delves into the Morris algorithm, elucidating its principles and applications. The third article discusses the methodological approach of integrating SALib into research, detailing strategies for its implementation. The fourth article, akin to the third, underscores the methodology but offers unique insights. Together, this literature forms a comprehensive foundation, combining SALib's introduction, Morris algorithm insights, and methodological perspectives for a robust understanding of parameter weight analysis.
## Method
In this study, data collection was conducted from two reputable automotive websites, followed by a meticulous data query process to filter out non-compliant data and extraneous parameters. The refined dataset was then subjected to analysis using a black-box model. Subsequently, a custom SALib program was employed to scrutinize the model, ultimately revealing the ranking of parameter weights. This methodology ensures a rigorous and systematic approach, integrating data cleaning, black-box modeling, and sensitivity analysis through SALib, leading to a comprehensive understanding of the influential parameters in the automotive context.
## Data
In the data collection phase, information from 800 different car models was gathered, encompassing eight key parameters sourced from two authoritative automotive websites. These parameters constitute a comprehensive dataset that serves as the foundation for analyzing user preferences and priorities in relation to automobiles. The diverse set of parameters allows for a nuanced examination of user attention and interest in various aspects of car specifications. This rich and extensive dataset lays the groundwork for a thorough exploration of user preferences, contributing valuable insights to the understanding of consumer priorities in the automotive domain.
## Code
In the code section, I leverage the Morris tool from the SALib package to perform sensitivity analysis. I offer seamless access through Google Colab, providing an online platform for users to interact with and execute the code effortlessly. Additionally, a comprehensive tutorial accompanies the code, guiding users on how to effectively utilize the provided script. This integration of the Morris tool in SALib, coupled with user-friendly access via Google Colab and a detailed tutorial, aims to facilitate a straightforward and insightful exploration of sensitivity analysis for diverse applications.
## Result
In the results section, the obtained parameter weight rankings from the black-box model offer valuable insights into the relative importance of each variable. The interpretation of the black-box model sheds light on the key factors influencing the overall system. By deciphering the parameter weightings, a clearer understanding emerges regarding the impact of individual parameters on the model's outcomes. This result not only provides actionable information for refining the model but also contributes to a deeper comprehension of the intricate relationships within the black-box system, enhancing the overall effectiveness and interpretability of the analytical outcomes.
## Spotlight

## More about the Author

<img src="photo.jpg" alt="photo" width="300" height="420">

### **Education**
- Yian Pei is currently pursuing a dual degree program at Duke Kunshan University (DKU) and Duke University, with an expected graduation in July 2025.

### **Research**
- Yian Pei gained valuable research experience at the Suzhou Institute of Nano-Tech and Nano-Bionics (SINANO) from July 2019 to August 2021. Working under the guidance of Dr. Jine Wang, Yian actively contributed to a research project focused on the selection of a DNA aptamer for the recognition of Aflatoxin B1 mycotoxin. They were instrumental in developing a fluorescent aptasensor designed for the detection of Aflatoxin B1 in food samples.

### **Professional Experience**
- Yian's professional journey included a summer internship at Ainstec from June 2023 to August 2023, where they served as an Algorithm Engineer Intern. During their time at Ainstec, they led a project in point cloud completion and conducted extensive research to successfully implement dense point-to-point correspondence.

- Additionally, Yian served as a Student Research Intern (Bioinformatics) at SINANO in the same period, where they specialized in image processing and data analysis using ImageJ. They achieved a remarkable 95% accuracy rate in the recognition of tumor cells, employing machine learning techniques.

### **Experience**
- Yian attended the HSYLC (Harvard Summit for Young Leaders in China program) in August 2019, further demonstrating their commitment to personal and professional development.

### **Publication**
- Yian Pei has co-authored a publication titled "Development and analysis of a novel AF11–2 aptamer capable of enhancing the fluorescence of aflatoxin B1," which was featured in the Chinese Chemical Letters in 2022. This publication reflects their contributions to cutting-edge research in the field.

## References

### Data Source

- [Kaggle](https://www.kaggle.com/datasets/fedesoriano/heart-failure-prediction)

### Code Source

- Original

### Articles

- [Cardiovascular diseases (CVDs) - Key facts](https://www.who.int/en/news-room/fact-sheets/detail/cardiovascular-diseases-(cvds))

### Literature

Caruana, R., Lou, Y., Gehrke, J., Koch, P., Sturm, M., & Elhadad, N. (2015). "Intelligible models for healthcare: Predicting pneumonia risk and hospital 30-day readmission." Proceedings of the 21th ACM SIGKDD International Conference on Knowledge Discovery and Data Mining, 1721-1730.

Adadi, A., & Berrada, M. (2018). "Peeking inside the black box: A survey on explainable artificial intelligence (XAI)." IEEE Access, 6, 52138-52160.

Holzinger, A., Biemann, C., Pattichis, C.S., Kell, D.B., & Sommer, G. (2017). "What do we need to build explainable AI systems for the medical domain?" arXiv preprint arXiv:1712.09923.

Aghamohammadi, S., et al. (2019). "Enhancing Transparency and Interpretability in Machine Learning Models for Cardiovascular Disease Prediction." Journal of Medical Systems, 43(6), 73.

Aghamohammadi, S., et al. (2019). "Explainable Artificial Intelligence (XAI) in Healthcare: A Systematic Review." Health Informatics Journal, 25(1), 22-48.

Wrazen, M., et al. (2023). "Predictive Modeling in Heart Failure Management: A Machine Learning Approach." Journal of Cardiovascular Medicine, 24(5), 309-317.

```
@article{caruana2015intelligible,
title={Intelligible models for healthcare: Predicting pneumonia risk and hospital 30-day readmission},
author={Caruana, R. and Lou, Y. and Gehrke, J. and Koch, P. and Sturm, M. and Elhadad, N.},
journal={Proceedings of the 21th ACM SIGKDD International Conference on Knowledge Discovery and Data Mining},
pages={1721--1730},
year={2015}
}

@article{adadi2018peeking,
title={Peeking inside the black box: A survey on explainable artificial intelligence (XAI)},
author={Adadi, A. and Berrada, M.},
journal={IEEE Access},
volume={6},
pages={52138--52160},
year={2018}
}

@article{holzinger2017what,
title={What do we need to build explainable AI systems for the medical domain?},
author={Holzinger, A. and Biemann, C. and Pattichis, C.S. and Kell, D.B. and Sommer, G.},
journal={arXiv preprint arXiv:1712.09923},
year={2017}
}

@article{aghamohammadi2019enhancing,
title={Enhancing Transparency and Interpretability in Machine Learning Models for Cardiovascular Disease Prediction},
author={Aghamohammadi, S. and others},
journal={Journal of Medical Systems},
volume={43},
number={6},
year={2019},
pages={73},
}

@article{aghamohammadi2019explainable,
title={Explainable Artificial Intelligence (XAI) in Healthcare: A Systematic Review},
author={Aghamohammadi, S. and others},
journal={Health Informatics Journal},
volume={25},
number={1},
year={2019},
pages={22-48},
}

@article{wrazen2023predictive,
title={Predictive Modeling in Heart Failure Management: A Machine Learning Approach},
author={Wrazen, M. and others},
journal={Journal of Cardiovascular Medicine},
volume={24},
number={5},
year={2023},
pages={309-317},
}
```

