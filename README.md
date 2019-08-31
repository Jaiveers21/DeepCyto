# DeepCyto
The future of medical diagnostics: uses deep learning models on mass cytometry data to predict and detect diseases. 

  Deep learning models on mass cytometry (CyTOF) data furnish boundless opportunities for the application of 
artificial intelligence in the detection and prediction of disease. Mass cytometry is an immunological technique where 
antibodies of cell samples, such as that of whole blood, are marked with heavy metals to simultaneously measure 40 or more 
protein markers at the single-cell level. Capturing the characteristics of immune cells in great detail, the rich information 
provided by CyTOF data can be used for clinical purposes. To these ends, specific indicators can be found and analyzed within 
such data to predict diseases, a feat that artificial intelligence has proven to be able to do well. In particular, deep 
learning models, offering benefits such as no requirements for feature engineering, can be used to predict clinical features 
using this raw CyTOF data. 
	We have developed a convolutional neural network tailored for raw CyTOF data, capable of disease diagnosis and prognosis. 
Specifically, we utilized deep learning models on CyTOF data obtained through the ImmPort Database from multiple heterogeneous 
studies, offering a more realistic application of computational-driven disease diagnostics in a clinical setting. From ImmPort,
the large amounts of CyTOF and general clinical data allow for the training of deep learning models. 
  We have initially applied this model to detect CMV infections. Not to be mistaken for a trivial ailment, CMV is a latent 
virus responsible for an asymptomatic infection that affects over half of all adults in America by age 40. Due to the 
asymptomatic nature of the infection, detecting it with immune cell profiles has long been a challenge. As a result, the 
developed deep learning model is a proof of concept, indicating the opportunity for future applications in diagnostics for 
other diseases if it is possible to predict an individual’s CMV infection status. 
  In fact, after being trained with curated and harmonized data, the model demonstrates that such data is indeed learnable, with 
preliminary models even achieving up to 70% in validation accuracy. This success, despite the heterogeneity in the data, 
suggests the ability to apply this method for other diseases as well, allowing for clinically relevant and realistic 
enhancements within the field of computational immunology and for contemporary healthcare. 


