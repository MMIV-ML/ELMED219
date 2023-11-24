# ELMED219: Artificial intelligence and computational medicine

<img src="./assets/GPT-MedAI.png" width="300"> <br>

If you have a subscription to [ChatGPT Pluss](https://openai.com/blog/chatgpt-plus), you can also try out the the [**Medical AI Assistant (UiBmed - ELMED219 & BMED365)**](https://chat.openai.com/g/g-d90dfN17H-medical-ai-assistant-uibmed-elmed219-bmed365) and see if you can get it to answer some of your questions.

----
<!--
<p>

[<img src="https://deepnote.com/buttons/launch-in-deepnote-small.svg">](https://deepnote.com/launch?url=https%3A%2F%2Fgithub.com%2Fmmiv-ml%2FELMED219) &nbsp; [![kaggle](https://camo.githubusercontent.com/a08ca511178e691ace596a95d334f73cf4ce06e83a5c4a5169b8bb68cac27bef/68747470733a2f2f6b6167676c652e636f6d2f7374617469632f696d616765732f6f70656e2d696e2d6b6167676c652e737667)](https://www.kaggle.com/alexanderlundervold/code) &nbsp;  [![Google Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/MMIV-ML/ELMED219/blob/main/) &nbsp; [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/MMIV-ML/ELMED219/HEAD) &nbsp; [![nbviewer](https://raw.githubusercontent.com/jupyter/design/master/logos/Badges/nbviewer_badge.svg)](https://nbviewer.org/github/MMIV-ML/ELMED219/tree/main/)
</p>
-->

The [course](https://www.uib.no/en/course/BMED365) is offered by the [Department of Biomedicine](https://www.uib.no/en/biomedisin) (UiB) in collaboration with the [Department of Computer science, Electrical engineering and Mathematical sciences](https://www.hvl.no/en/about/management/faculty-of-engineering-and-science/department-of-computer-science-electrical-engineering-and-mathematical-sciences-ny-side) at the Western Norway University of Applied Sciences (HVL), and the Medical AI group at [Mohn Medical Imaging and Visualization Center](https://mmiv.no) (MMIV).

<img src="./assets/elmed219_logo.png" width="700"> <br>

The objective and content of the course address: The computational mindset, imaging, modeling, machine learning, and AI in future medicine, as well as ethical and regulatory aspects of AI. The course is a guided "journey" with a hands-on component through selected computational modeling techniques within biomedical and clinical applications. Examples, demonstrations, and tasks will be related to in vivo imaging (MRI) and segmentation, biomarkers and prediction, network analysis ("patient similarity networks"), multimodal data, as well as large language models ("foundation models") within medicine and health. Throughout the course, students will use principles and modern tools for data analysis, machine learning, and generative AI (e.g. ChatGPT) within medical applications. This will give the students an introduction to Python and Jupyter notebooks, use of the "cloud" for access to open data, calculations, and knowledge, as well as insight into and rationale for "open science" and "reproducible research". All course material is openly available on this GitHub repository.


- This repository contains most of the course material. Students enrolled in the course will also find some practical information at [MittUiB](https://mitt.uib.no/courses/45080).

- On your own, you are encouraged to spend approximately four hours completing at least one DataCamp course (remember to use the link on MittUiB for free access to DataCamp). Which DataCamp course you're encouraged to do depends on your previous programming experience:<br>
  - No Python programming experience? Complete the course [Introduction to Python](https://learn.datacamp.com/courses/intro-to-python-for-data-science)<br>
  - Know some Python, but no machine learning? Complete the course [Supervised Learning with scikit-learn](https://learn.datacamp.com/courses/supervised-learning-with-scikit-learn)<br>
  - Know the fundamentals of machine learning in Python? Can you pass the *Machine Learning Fundamentals Assessment*? Complete the course [Biomedical Image Analysis in Python](https://learn.datacamp.com/courses/biomedical-image-analysis-in-python)   

-  For **academic questions** about the course, contact course coordinator [Arvid Lundervold](https://www.uib.no/en/persons/Arvid.Lundervold) (UiB).

- For **practical or administrative inquiries**, contact the Studies Section at the Department of Biomedicine at studie.biomed@uib.no


<img src="./assets/cc_by_sa.png" width="75"> The content for the course is offered with a <b><a href="http://creativecommons.org/licenses/by-sa/4.0">CC BY-SA 4.0</a></b> license unless otherwise stated.

--------

# Tentative time schedule


| **TIME**                    | ACTIVITY                                                                               |
| --------------------------- | -------------------------------------------------------------------------------------- |
| **Week 1<br> Tue, Jan 2**   |                                                                                        |
| _On your own_               | Get an overview of the course; installation of software and/or test out Google Colab   |
|                             | Follow the instructions at [MittUiB](https://mitt.uib.no/courses/45080)                |
| **Week 1<br> Wed, Jan 3**   |                                                                                        |
| 10:15-14:00                 | Information, SW-installation<br> Motivation lectures<br>&nbsp;- [Computational medicine](https://docs.google.com/presentation/d/e/2PACX-1vTv4m61mE_mq4_L3v1Yzijww1axoZI7Jt5zUizug8pT3l5IY8CQ_82Al921P_HJLeXCBJJVeWl4bhvN/pub?start=false&loop=false&delayms=3000) <br>&nbsp;- [Medical AI](https://www.dropbox.com/s/7ciwh1bxh5wyat4/ELMED219%20-%202023%20-Medical%20AI.pdf?dl=1)     |
|                             | *Arvid Lundervold / N.N.*   |                                |
| **Week 1<br>Thu, Jan 4**    |                                                                                        |
| 14:15-15:00                 | About the course <br> [Tools], [teams] and [project]                                   |
|                             | *Arvid Lundervold  / N.N.*                                                             |
| 15:15-16:00                 | [LAB 0: Introduction to theory and tools for machine learning](./Lab0-ML)                         |
|                             | *Ben Bjørsvik / Arvid Lundervold*                                                      |
| **Week 1<br>Fri, Jan 5**    |                                                                                        |
| 10:15-11:00                 | [LAB 0: Introduction to theory and tools for machine learning] cont.                   |
|                             | *Ben Bjørsvik / Arvid Lundervold*                                                      |
| 11:15-13:00                 |  [LAB 1: Brain imaging (mpMRI) in glioblastoma]                                        |
|                             | *Arvid Lundervold*                                                                     |
|                             |                                                                                        |
| **Week 2<br>Tue, Jan 9**    |                                                                                        |
| 08:15-13:00                 | [Lab 2: Deep learning]                                                                 |
|                             | *N.N. / Arvid Lundervold*                                                              |
| **Week 2<br>Fri, Jan 12**   |                                                                                        |
| 08:15-13:00                 | [Lab 3: Generative AI / Large Language Models]                                         |
|                             | *N.N. / Arvid Lundervold*                                                              |
| **Week 3<br>Team project**  |  Joint with BMED365 - Working on project in interdisciplinary teams                   |
| **Week 3<br>Tue, Jan 16**   |                                                                                        |
| 09:00-12:00                 | Crash-course in Python programming                                                     |
|                             | *Ben Bjørsvik*                                                                         |
| 13:00-16:00                 | Meet-up for team project brainstorming and coaching                                    |
|                             | *Arvid Lundervold / N.N.*                                                              |
|  **Week 4<br>Wed, Jan 24**  |                                                                                        |
| 08:15-10:00                 | Project presentations by team  (jointly with BMED365)                                 |
|                             | *Arvid Lundervold / N.N.*                                                             |
| **Week 4<br>Fri, Jan 26**   |                                                                                       |
| 16:00                       | Deadline for the Team Project Report - joint with BMED365 (hand in via MittUiB)       |
|**Fri, Jan 26** | 
||**Home exam**: Duration: 2 hours;  <br>Assignment is handed out: 26.01.2024, 13:00; <br>Submission deadline: 26.01.2024, 15:00; <br>Examination system: Inspera Digital exam



### Previous versions of the ELMED219 course

| **Year**                    | Link             |
| --------------------------- |  --              | 
|2024 |https://github.com/MMIV-ML/ELMED219       |
|2023 |https://github.com/MMIV-ML/ELMED219-2023       |
|2022 |https://github.com/MMIV-ML/ELMED219-2022  |
|2021 |https://github.com/MMIV-ML/ELMED219-2021  |
|2020 |https://github.com/MMIV-ML/ELMED219-2020  |
|2019 |https://github.com/MMIV-ML/ELMED219x-2019 |

### Previous versions of the BMED360 course
_"In Vivo Imaging and Physiological Modelling"_

| **Year**                    | Link             |
| --------------------------- |  --              | 
|2021 |https://github.com/computational-medicine/BMED360-2021 |
|2020 |https://github.com/computational-medicine/BMED360-2020 |


### Previous versions of the BMED365 course
_"Computational imaging, modelling and AI in biomedicine"_

| **Year**                    | Link             |
| --------------------------- |  --              | 
|2024 |https://github.com/MMIV-ML/BMED365 |
