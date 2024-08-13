# GSRDA

This is Generative Semi-Reflective Time Series Data Augmentation method based on the work of Dawson and O'Shea. We utilized this as a strategy to generate close to realistic synthetic data to help in the classification of impaired driving from limited simulator data samples. Throughout this project we generated 100% GSRDA examples, and other versions where we replaced 50% and 20% of the samples with GSRDA (and matched the endpoints) to experimientally test which kind of synthetic data improved performance best. There is also a version of this that replaces 50% and 20% with a random walk which we also used as a base comparison for our method.

## What you will find in this repository.

- Impaired driving simulator data.
- Python code for generating the augmented semi-synthetic data frames for all types of augmentations.
- Deep model code used: built-in Inception Time Plus from TSAI.
- Visulaizations for the data augmentation.


## References

Koch, K., Maritsch, M., Van Weenen, E., Feuerriegel, S., Pfäffli, M., Fleisch, E., Weinmann, W., & Wortmann, F. (2023). Leveraging driver vehicle and environment interaction: Machine learning using driver monitoring cameras to detect drunk driving. In Proceedings of the 2023 CHI Conference on Human Factors in Computing Systems (CHI '23), Article 322. Association for Computing Machinery. New York, NY, USA. https://doi.org/10.1145/3544548.3580975

McDonald, A. D., Schwarz, C., Lee, J. D., & Brown, T. L. (2012). Real-Time Detection of Drowsiness Related Lane Departures Using Steering Wheel Angle. Proceedings of the Human Factors and Ergonomics Society Annual Meeting, 56(1), 2201-2205. https://doi.org/10.1177/1071181312561464

Çetinkaya, M., & Acarman, T. (2023). Driver impairment detection using decision tree based feature selection and classification. Results in Engineering, 18, 101025. https://doi.org/10.1016/j.rineng.2023.101025

Simmons, S. M., Caird, J. K., Sterzer, F., & Asbridge, M. (2022). The effects of cannabis and alcohol on driving performance and driver behaviour: A systematic review and meta-analysis. Addiction, 117(7), 1843-1856. https://doi.org/10.1111/add.15770

Shorten, C., & Khoshgoftaar, T. M. (2019). A survey on Image Data Augmentation for Deep Learning. Journal of Big Data, 6(1), 60. https://doi.org/10.1186/s40537-019-0197-0

Iwana, B. K., & Uchida, S. (2021). An empirical survey of data augmentation for time series classification with neural networks. PLOS ONE, 16(7), e0254841. https://doi.org/10.1371/journal.pone.0254841

Gao, Z., Li, L., & Xu, T. (2023). Data Augmentation for Time-Series Classification: A Comprehensive Survey. arXiv:2310.10060v4. Retrieved from https://arxiv.org/abs/2310.10060v4

Nanni, L., Paci, M., Brahnam, S., & Lumini, A. (2021). Comparison of Different Image Data Augmentation Approaches. Journal of Imaging, 7(12), 254. https://doi.org/10.3390/jimaging7120254
