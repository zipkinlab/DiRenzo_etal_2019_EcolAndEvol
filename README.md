# [Disease structured N-Mixture models: A practical guide to model disease dynamics using count data](https://onlinelibrary.wiley.com/doi/full/10.1002/ece3.4849)

### [Graziella V. DiRenzo](https://grazielladirenzo.weebly.com), [Christian Che-Castaldo](https://github.com/CCheCastaldo), [Sarah P. Saunders](https://sarahpsaunders.wordpress.com/), [Evan H. Campbell Grant](https://www.usgs.gov/staff-profiles/evan-grant?qt-staff_profile_science_products=0#qt-staff_profile_science_products), & [Elise F. Zipkin](https://msu.edu/user/ezipkin/)

### Ecology & Evolution

### Please contact the first author for questions about the code: Graziella DiRenzo (grace.direnzo@gmail.com)
__________________________________________________________________________________________________________________________________________

## Abstract: 
1.  Obtaining inferences on disease dynamics (e.g., host population size, pathogen prevalence, transmission rate, host survival probability) typically requires marking and tracking individuals over time. While multistate mark–recapture models can produce high quality inference, these techniques are difficult to employ at large spatial and long temporal scales or in small remnant host populations decimated by virulent pathogens, where low recapture rates may preclude the use of mark–recapture techniques. 

2. Recently developed N-mixture models offer a statistical framework for estimating wildlife disease dynamics from count data. N-mixture models are a type of state-space model in which observation error is attributed to failing to detect some individuals when they are present (i.e., false negatives). The analysis approach uses repeated surveys of sites over a period of population closure to estimate detection probability. 

3. We review the challenges of modeling disease dynamics and describe how N-mixture models can be used to estimate common metrics, including pathogen prevalence, transmission, and recovery rates while account for imperfect host and pathogen detection. We also offer a perspective on future research directions at the intersection of quantitative and disease ecology, including the estimation of false positives in pathogen presence, spatially-explicit disease-structured N-mixture models, and the integration of other data types with count data to inform disease dynamics.

4. Managers rely on accurate and precise estimates of disease dynamics to develop strategies to mitigate pathogen impacts on host populations. At a time when pathogens pose one of the greatest threats to biodiversity, statistical methods that lead to robust inferences on host populations are critically needed for rapid, rather than incremental, assessments of the impacts of emerging infectious diseases.

## Code

Rmarkdown version: [Appendix](https://github.com/zipkinlab/DiRenzo_etal_2019_EcolAndEvol/blob/master/Appendix_09_Nov_2018.Rmd)

PDF version: [Appendix](https://github.com/zipkinlab/DiRenzo_etal_2019_EcolAndEvol/blob/master/Appendix_09_Nov_2018.pdf)

HTML version: [Appendix](https://github.com/zipkinlab/DiRenzo_etal_2019_EcolAndEvol/blob/master/Appendix_09_Nov_2018.html)

Code:

[Disease-structured N-mixture model (single season)](https://github.com/zipkinlab/DiRenzo_etal_2019_EcolAndEvol/blob/master/model.txt)

[N-mixture model with imperfect sampling and lab detection of pathogen](https://github.com/zipkinlab/DiRenzo_etal_2019_EcolAndEvol/blob/master/model_sampling.txt)

Images/Figures: 

[Observation matrix](https://github.com/zipkinlab/DiRenzo_etal_2019_EcolAndEvol/blob/master/piMatrix.png)

[State matrix](https://github.com/zipkinlab/DiRenzo_etal_2019_EcolAndEvol/blob/master/psiMatrix.png)

LaTex code:

[Observation matrix](https://github.com/zipkinlab/DiRenzo_etal_2019_EcolAndEvol/blob/master/piMatrix.tex)

[State matrix](https://github.com/zipkinlab/DiRenzo_etal_2019_EcolAndEvol/blob/master/psiMatrix.tex)

Style:

[Rmarkdown style](https://github.com/zipkinlab/DiRenzo_etal_2019_EcolAndEvol/blob/master/style.css) 

## Data

All data is simulated in the Code.
