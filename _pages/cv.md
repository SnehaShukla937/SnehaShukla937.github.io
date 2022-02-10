---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

<!-- <embed src="../files/Fellowship_CV_Anup_Kumar_Gupta.pdf" type="application/pdf" /> -->

Education
=========
* Ph.D. in Computer Science and Engineering, Indian Institute of Technology Indore (Aug. 2021 - present)
* M.Tech. in Information Technology, National Institute of Technology Raipur (July 2016- July 2018)
* B.E. in Electronics and Telecommunication, Chhattisgarh Swami Vivekananda Technical University, Bhilai (Aug. 2011 - June 2015)


Projects
=========
* Speech Recognition System
  * To tackle the problem of pronunciation in the English language, we have designed a Convolution Neural Network (CNN) & Long Short Term Memory (LSTM) based speech recognition system that can recognise recorded mispronounced words.
  * Stages Involved: Data prepossessing, MFCC (Mel Frequency Cepstral Coefficients) feature extraction, model training and testing.
  
* Electroencephalogram (EEG) based Brain-Computer Interface (BCI) systems using machine learning techniques
  * Enhancing the performance of EEG based BCI systems for motor imagery task by classifying the EEG data and analyse their performance utilising various machine learning techniques such as bagging, boosting, k nearest neighbour (KNN), naive bayes.
  * Stages involved: Data prepossessing, short-time Fourier transform and wavelet feature extraction, rank-based feature selection, classification.

* Face recognition based real-time attendance system
  * A computer vision system that can recognise real time faces and record the information to mark attendance.
  * Stages involved: Image loading, finding a face in the image, compare training and testing face, record information.   


Publications
======
  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Work experience
===============

* Indian Institute of Technology Indore  (Indore, Madhya Pradesh, Jan. 2021 - Present)
  * Project Fellow (JRF)
  * Working in the project entitled **Heart rate monitoring from non-contact face videos using deep learning** under the supervision of Dr. Puneet Gupta.

* National Informatics Centre (NIC) (Raipur, Chhattisgarh, India July 2018 - Dec. 2019)
  * Software Developer in Research and Development wing of Department of School Education.
  * Involved in the research and development group of a school education project, where I have designed a speech recognition system utilising deep learning techniques. The vision of this project is to tackle the problem of pronunciation in the English language.
  * Worked on data analytics and report generation on state education data using SQL queries, SQLite3, pandas, reportlab, matplotlib and several other python libraries.
