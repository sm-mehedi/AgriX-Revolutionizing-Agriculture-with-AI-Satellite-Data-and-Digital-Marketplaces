//parash


//taha

//mehedi
<h2>Literature Review</h2>
Recent research in smart agriculture underscores the growing use of Artificial Intelligence (AI), Internet of Things (IoT), and data modeling to support real-time monitoring, forecasting, and automation aimed at improving yield, efficiency, and sustainability.

O’Grady et al. designed a climate-smart decision-support system integrating global weather data to enhance forecasting capabilities, though their system encountered challenges with data quality and intellectual property rights [1]. Budaev et al. developed a multi-agent AI-based platform utilizing Normalized Difference Vegetation Index (NDVI) and soil data for real-time farm resource planning, resulting in improved yield outcomes and transparency [2]. Inspired by audit risk models, Wijaya et al. demonstrated how AI-based prediction techniques could inform agricultural decision-making [3], [18]. Kujawa applied radial basis function (RBF) neural networks to detect grain pests based on physical attributes [4]. Gardezi employed machine learning and explainable AI methods to assist farmers in making environmentally sound decisions [5], while Linaza advanced autonomous farming through simultaneous localization and mapping (SLAM), stereo vision, and deep learning-based robotics [6].

Several studies addressed yield prediction. Dhal combined LSTM, ARIMA, and Random Forest models for forecasting crop productivity [7]. Mahibha employed drone imagery with AI for early-stage disease identification [8]. Ravichandran introduced the SAgric-IoT framework, leveraging convolutional neural networks (CNNs) for greenhouse surveillance and automated irrigation [9]. Arya merged sensor, drone, and satellite data with machine learning algorithms to optimize agricultural planning [10].

Soil moisture prediction has also evolved, with Nijaguna using satellite imagery in conjunction with Bi-GRU and CNN models [11], Singh utilizing Sentinel data with artificial neural networks (ANNs) [12], Sharma highlighting LSTM’s superior performance [13], and Hassan applying XGBoost and support vector regression (SVR) for soil compaction analysis [14].

Advancements in plant disease detection have been notable. Saleem proposed AgriLeafNet, integrating NASNetMobile and few-shot learning for leaf disease recognition [15]. Falaschetti developed a lightweight CNN optimized for mobile use [16], and Gong applied YOLOv3 and Faster R-CNN to identify apple leaf diseases [17].

Trends in smart agriculture adoption have been documented. Slimani’s bibliometric review noted a surge in AI-drone integration in the field [19], and Mahibha emphasized AI’s pivotal role in both academic research and technology dissemination [20].

Digital agriculture platforms have emerged as significant enablers. Patil introduced an AI-based advisory and marketplace system, widely adopted by farmers for its practical utility [21]. Chougule’s work featured a multilingual platform combining AI, speech recognition, and blockchain-based governance [22]. Alam contributed a rural service delivery framework [23], while Asolo developed a chatbot-powered decision support system for sustainable agricultural practices [24].

Fatih Aslan applied deep learning (CNNs) and ensemble models to Sentinel-2 satellite data, achieving highly accurate yield predictions across various crops, with RMSE as low as 0.047–0.62 t/ha [26]. In the domain of rural digitization, Thi Tuan Linh Pham identified four critical digital skills that enabled Vietnamese farmers to adopt e-commerce in the green tea sector, emphasizing B2B marketplace readiness [27].

In the context of community engagement, Altman and Zube explored human interaction in public spaces through observations and interviews, yielding insights that may inform the design of rural agricultural event-sharing platforms [28].

Despite these promising developments, existing software systems often address only isolated functions—such as forecasting, disease identification, or market access—without offering a fully integrated solution. Most lack support for local languages and do not accommodate features such as rural community event sharing or real-time multi-source data fusion.

<h3>Existing Software Solutions in the Problem Area</h3>
The reviewed studies have yielded various domain-specific tools addressing key agricultural challenges:

<strong>Climate-smart systems</strong>: O’Grady’s weather-based forecasting tool [1].

<strong>AI-based resource planning</strong>: Budaev’s multi-agent farm planning system [2].

<strong>Yield and disease prediction</strong>: Mahibha [8], Ravichandran (SAgric-IoT) [9], and Fatih Aslan [26].

<strong>Soil monitoring tools</strong>: Nijaguna [11], Singh [12], Sharma [13], Hassan [14].

<strong>Disease detection solutions</strong>: Saleem’s AgriLeafNet [15], Falaschetti [16], Gong [17].

<strong>Digital platforms</strong>: Patil’s AI-powered advisory system [21], Chougule’s multilingual, blockchain-integrated platform [22], Alam’s rural delivery framework [23], and Asolo’s chatbot DSS [24].

Although these systems demonstrate technological maturity, they typically operate in silos and do not integrate critical features—such as localized AI chatbot support, cross-domain data fusion, or community event facilitation—into a cohesive platform.

<h3>Our Contribution</h3>
To address these gaps, the proposed solution—<em>AgriX</em>—offers an integrated platform combining:

AI-powered crop and poultry disease detection

Satellite-driven soil and yield analysis

A bilingual AI assistant (Bangla and English)

A digital B2B marketplace for farmers

Live rural event mapping and sharing tools

Real-time data fusion from weather, satellite, and user inputs

This unified system is designed specifically to empower smallholder farmers in regions like Bangladesh, where access to localized, comprehensive, and language-aware digital agriculture tools remains limited.




//shohaib







<div style="font-size: 0.95em; line-height: 1.5;"> [1] M. O’Grady et al., “Service design for climate-smart agriculture,” *Smart Agricultural Technology*, vol. 1, 2020. [2] D. Budaev et al., “Conceptual design of smart farming solution for precise agriculture,” *Int. J. Design & Nature and Ecodynamics*, vol. 13, no. 3, 2018. [3] J. R. T. Wijaya et al., “Artificial intelligence and audit quality,” *Fokus Ekonomi*, vol. 20, no. 1, 2025. [4] S. Kujawa and G. Niedbała, “Artificial neural networks in agriculture,” *Agriculture*, vol. 11, no. 6, 2021. [5] M. Gardezi et al., “AI in farming: Building trust,” *Agronomy Journal*, vol. 116, no. 3, 2024. [6] M. T. Linaza et al., “AI for sustainable precision agriculture,” *Agronomy*, vol. 11, no. 6, 2021. [7] S. B. Dhal and D. Kar, “AI-driven forecasting,” *Forecasting*, vol. 6, no. 4, 2024. [8] G. Mahibha and P. Balasubramanian, “Impact of AI in agriculture,” *CARJ*, vol. 11, no. 1, 2023. [9] D. Ravichandran et al., “Digital agriculture via IoT and analytics,” *ICSGET Proc.*, vol. 02003, 2024. [10] K. Arya, “ML for smart agriculture,” unpublished, 2024. [11] G. S. Nijaguna et al., “WCM for soil moisture via satellite,” *Remote Sens.*, vol. 15, no. 8, 2023. [12] A. Singh and K. Gaurav, “Soil moisture estimation via DL,” *Scientific Reports*, vol. 13, 2023. [13] V. Sharma et al., “Soil moisture estimation using ML,” *EGU General Assembly*, 2025. [14] M. Hassan and E. Beshr, “Soil cone index prediction,” *Scientific Reports*, vol. 14, 2024. [15] S. Saleem et al., “AgriLeafNet: Multi-crop disease detection,” *Agronomy*, vol. 14, no. 10, 2024. [16] L. Falaschetti et al., “CNN-based plant disease detection,” *HardwareX*, vol. 12, 2022. [17] X. Gong and S. Zhang, “Deep learning for plant diseases,” *Plant Pathol. J.*, vol. 39, no. 4, 2023. [18] J. R. T. Wijaya et al., (duplicate) [19] H. Slimani et al., “AI and drone integration in agriculture,” *IJECE*, vol. 14, no. 1, 2024. [20] G. Mahibha and P. Balasubramanian, (duplicate) [21] P. Patil et al., “Farmers Network,” *IJARCCE*, vol. 14, no. 3, 2025. [22] O. A. Chougule et al., “E-Grampanchayat governance platform,” *IJARSCT*, vol. 5, no. 1, 2025. [23] F. Alam et al., “Bangla NLP and Transformer utility,” *HBKU & DU*, 2025. [24] E. Asolo et al., “AI chatbot DSS for sustainable farming,” *JDFEWS*, vol. 5, no. 1, 2024. [25] A. D. Jones and G. Ejeta, “Agriculture’s role in nutrition,” *Bull. WHO*, vol. 94, 2016. [26] M. F. Aslan et al., “AI techniques in yield estimation,” *Sustainability*, vol. 16, no. 18, 2024. [27] T. T. L. Pham et al., “Digital capabilities in agribusiness,” *EAI Trans. Scalable Info. Systems*, 2024. [28] I. Altman and E. H. Zube, *Public Places and Spaces*, Plenum Press, 1989. </div>
