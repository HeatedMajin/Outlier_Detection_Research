# Outlier_Detection_Research

## classical methods
* **LOF**
  * Markus M Breunig, Hans-Peter Kriegel, Raymond T Ng, and Jörg Sander. Lof: identifying densitybased
    local outliers. In ACM sigmod record, volume 29, pp. 93–104. ACM, 2000.

* **OC-SVM**
  * Bernhard Schölkopf, John C Platt, John Shawe-Taylor, Alex J Smola, and Robert C Williamson.
    Estimating the support of a high-dimensional distribution. Neural computation, 13(7):1443–1471,
    2001.



* uses **Benford’s Law** to identify anomalies in **social networks**
  * Samuel Maurus and Claudia Plant. Let’s see your digits: Anomalous-state detection using benford’s
    law. In Proceedings of the 23rd ACM SIGKDD International Conference on Knowledge Discovery
    and Data Mining, pp. 977–986. ACM, 2017.

* uses **Extreme Value Theory** to detect anomalies
  * Alban Siffer, Pierre-Alain Fouque, Alexandre Termier, and Christine Largouet. Anomaly detection
    in streams with extreme value theory. In Proceedings of the 23rd ACM SIGKDD International
    Conference on Knowledge Discovery and Data Mining, pp. 1067–1075. ACM, 2017

## specific type of data

* **spatially contextualized data**
  * Guanjie Zheng, Susan L Brantley, Thomas Lauvaux, and Zhenhui Li. Contextual spatial outlier
    detection with metric learning. In Proceedings of the 23rd ACM SIGKDD International Conference
    on Knowledge Discovery and Data Mining, pp. 2161–2170. ACM, 2017.

* **graph data**
  * Bryan Perozzi, Leman Akoglu, Patricia Iglesias Sánchez, and Emmanuel Müller. Focused clustering
    and outlier detection in large attributed graphs. In Proceedings of the 20th ACM SIGKDD
    international conference on Knowledge discovery and data mining, pp. 1346–1355. ACM, 2014.
  * Bryan Perozzi and Leman Akoglu. Scalable anomaly ranking of attributed neighborhoods. In
    Proceedings of the 2016 SIAM International Conference on Data Mining, pp. 207–215. SIAM,
    2016.
  * Jundong Li, Harsh Dani, Xia Hu, and Huan Liu. Radar: Residual analysis for anomaly detection
    in attributed networks. In Proceedings of the 26th International Joint Conference on Artificial
    Intelligence, pp. 2152–2158. AAAI Press, 2017.
  * Ninghao Liu, Xiao Huang, and Xia Hu. Accelerated local anomaly detection via resolving attributed
    networks. In Proceedings of the 26th International Joint Conference on Artificial Intelligence, pp.
    2337–2343. AAAI Press, 2017.
  * NetWalk: A Flexible Deep Embedding Approach for Anomaly Detection in Dynamic Networks Wenchao Yu, Wei Cheng, Charu C. Aggarwal, Kai Zhang, Haifeng Chen, Wei Wang. KDD,2018

## specific structure

* **energy**

  * （**DSEBM**）Shuangfei Zhai, Yu Cheng, Weining Lu, and Zhongfei Zhang. Deep structured energy based models for anomaly detection. arXiv preprint arXiv:1605.07717, 2016.

    

* **GAN**

  * （**AnoGAN**）Thomas Schlegl, Philipp Seeböck, Sebastian M Waldstein, Ursula Schmidt-Erfurth, and Georg Langs.Unsupervised anomaly detection with generative adversarial networks to guide marker discovery.In International Conference on Information Processing in Medical Imaging, pp. 146–157. Springer,2017.

  

* **autoencoders**

  * （**DAE**）Pascal Vincent, Hugo Larochelle, Yoshua Bengio, and Pierre-Antoine Manzagol. Extracting and composing robust features with denoising autoencoders. In International Conference on Machine learning, pp. 1096–1103. ACM, 2008.

  * Chong Zhou and Randy C Paffenroth. Anomaly detection with robust deep autoencoders. In
    Proceedings of the 23rd ACM SIGKDD International Conference on Knowledge Discovery and
    Data Mining, pp. 665–674. ACM, 2017.

  * （**DAGMM**）Bo Zong, Qi Song, Martin Renqiang Min, Wei Cheng, Cristian Lumezanu, Daeki Cho, and Haifeng Chen. Deep autoencoding gaussian mixture model for unsupervised anomaly detection. In International Conference on Learning Representations, 2018.

    

* **DCN**

  * Bo Yang, Xiao Fu, Nicholas D Sidiropoulos, and Mingyi Hong. Towards k-means-friendly spaces:
    Simultaneous deep learning and clustering. In International Conference on Machine Learning, pp.
    3861–3870, 2017.

## Active Anomaly Detection

- Nico Görnitz, Marius Kloft, Konrad Rieck, and Ulf Brefeld. Toward supervised anomaly detection.
  Journal of Artificial Intelligence Research, 46:235–262, 2013.

- （**LODA-AAD**）Shubhomoy Das, Weng-Keen Wong, Thomas Dietterich, Alan Fern, and Andrew Emmott. Incorporating expert feedback into active anomaly discovery. In International Conference on Data Mining (ICDM), pp. 853–858. IEEE, 2016.
- （**TREE-AAD**）Shubhomoy Das, Weng-Keen Wong, Alan Fern, Thomas G Dietterich, and Md Amran Siddiqui. Incorporating feedback into tree-based anomaly detection. Workshop on Interactive Data Exploration and Analytics (IDEA), 2017.
- UaiNets: From Unsupervised to Active Deep Anomaly Detection .Tiago Pimentel, Marianne Monteiro, Juliano Viana, Adriano Veloso, Nivio Ziviani,ICLR,2018 





## To be continue

- Yann LeCun, Sumit Chopra, Raia Hadsell, M Ranzato, and F Huang. A tutorial on energy-based learning. Predicting structured data, 1(0), 2006.


- Kyle Hundman, Valentino Constantinou, Christopher Laporte, Ian Colwell, and Tom Soderstrom. 2018. Detecting Spacecraft Anomalies Using LSTMs and Nonparametric Dynamic Thresholding. In Proceedings of the 24th ACM SIGKDD International Conference on Knowledge Discovery &#38; Data Mining (KDD ’18).ACM, New York, NY, USA, 387–395.


- 
  Daehyung Park, Yuuna Hoshi, and Charles C. Kemp. 2018. A Multimodal Anomaly Detector for Robot-Assisted Feeding Using an LSTM-Based Variational Autoencoder. IEEE Robotics and Automation Letters 3 (2018), 1544–1551

- Marco Fraccaro, Søren Kaae Sønderby, Ulrich Paquet, and Ole Winther. 2016.Sequential neural models with stochastic layers. In Advances in neural information processing systems. 2199–2207.
- Daehyung Park, Yuuna Hoshi, and Charles C. Kemp. 2018. A Multimodal Anomaly Detector for Robot-Assisted Feeding Using an LSTM-Based Variational Autoencoder. IEEE Robotics and Automation Letters 3 (2018), 1544–1551.
- Bo Zong, Qi Song, Martin Renqiang Min, Wei Cheng, Cristian Lumezanu, Daeki Cho, and Haifeng Chen. 2018. Deep autoencoding gaussian mixture model for unsupervised anomaly detection. In International Conference on Learning Representations.
- Diederik P. Kingma and Max Welling. 2014. Auto-Encoding Variational Bayes. In
  Proceedings of the Second International Conference on Learning Representations
  (ICLR 2014).