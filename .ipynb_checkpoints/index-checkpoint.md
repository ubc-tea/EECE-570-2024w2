---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

# For courses with a single offering in the _config.yml,
# uncomment the following line and comment out the course-multi line

# layout: course-single
layout: course-multi
---

# <a name="description">Overview</a>

{{ site.description }}

## <a name="description">Course Description</a>

* This is a Special Topics course focusing on the foundations of computer vision and machine learning/ deep learning methods for computer vision tasks. The students are expected to have obtained a solid
background in machine learning, linear algebra, and coding skills.
* This course is a combination of lectures and student presentations. We plan to read and discuss recent research papers on the intersection between computer vision and machine learning. We plan to invite internal (within the department) and external speakers to give guest lectures to give introductory and state-of-the-art developments in the area of computer vision and machine learning.
* This course satisfies the ECE graduate program requirement.
* Piazza: [https://piazza.com/ubc.ca/winterterm22022/eece570](https://piazza.com/ubc.ca/winterterm22022/eece570)

{% include resources.html content=site.goals %}

## <a name="contact">Contacts</a>
* Instructor: Dr. Xiaoxiao Li (xiaoxiao.li@ece.ubc.ca)
* TA: Chun-Yin Huang (chunyinhuang17@gmail.com)
* TA: Sana Ayromlou (ayromlous@gmail.com)
* Email: include ‘[EECE 570]’ in the subject.

{% include resources.html content=site.resources %}

## <a name="time-and-location">Time and Location</a>

* Location:
Tue/Thu ∥ 11:00 am – 12:30 pm ∥ SPPH B151
* Zoom participation ID:
[https://ubc.zoom.us/j/65807504716?pwd=RnV0Z2dHR1NCMkcwcnVYVmluZ2RRdz09](https://pythonintro-yorgey.notebooks.azure.com/j/notebooks/PythonIntro.ipynb)
* TA Office Hours: TBA
* Instructor Office Hours: Thursday afternoon (by appointment only)

{% include resources.html content=site.extra-resources %}


## <a name="reading-and-presentation">Reading and Presentation</a>
* During each class meeting, we will have student presentations and discussions of selected papers.  The tentative schedule below lists tentative topics for each class and suggested papers.  

* Students taking the course are expected to read all selected papers. The presenter needs to write a review for the paper to be presented. Each review should be submitted one day before its presentation and discussion. Please refer to lecture 1's course notes on how to write a review. The review needs to cover 1) summary; 2) pros; 3) cons; and 4) future direction.

 
* There are 3 parts for each presentation: 
  * Problem statement, a brief overview of the state-of-the-art
  * Key idea of the paper
  * Strengths, weaknesses and future directions
	

* The total time allocated for each paper is 40 minutes with 25 mins presentation and 15 mins discussion.  We suggest you prepare in advance and do not exceed 40 minutes to leave 40 minutes for another presentation.

* We welcome students to suggest their interested papers.  If students are interested in substitute papers, after signing up for desired time slots, the student should discuss with the instructor at least one week in advance to have time to make an announcement.  

## <a name="grading">Grading</a>
* Paper Readings and Presentations: 30% 
  * Read the selected paper(s) and submit review
  * Present the selected paper
  * Lead discussion in the classroom


* Course participants: 10%
  * You must show up on your presentation date. No show will lead to failing the course. 
  * Grade for your classmate's presentation. If you cannot attend the presentation (two chances over the term), please let TA and instructor know. Otherwise, -1 point each time. 


* Project proposal (2 pages): 20%
* Final project (at least 4 pages): 40%
  * A computer vision project that is related to the course topic. You have the flexibility to choose the topics. More details will be released later. **No Teamwork allowed**.
  * *Passing the course does on conditional on if you pass the final project*.

* Late submission will result in *0.8 decay per day. Extension is only accepted via applying for [Academic Concession](https://academicservices.engineering.ubc.ca/exams-grades/academic-concession/).


## Computational Resources

* GPU computing is required for this class. I strongly recommend to Google Colab or use your
own/lab’s GPU since that is the most convenient way of writing and testing code with GUI. [Click
here](https://colab.research.google.com/github/cs231n/cs231n.github.io/blob/master/python-colab.ipynb) to try out the Colab tutorial. You can also consider using other computational resources
offered by UBC.

## Optional Textbooks

* Friedman, Jerome, Trevor Hastie, and Robert Tibshirani. The elements of statistical learning.
Vol. 1. No. 10. New York: Springer series in statistics, 2001.
* Richard Szeliski. Computer Vision: Algorithms and Applications , 2022.
* Goodfellow, Ian, Yoshua Bengio, Aaron Courville, and Yoshua Bengio. Deep learning. Vol.
1, no. 2. Cambridge: MIT press, 2016.
* Torfi, Amirsina. [Deep Learning Roadmap](https://www.machinelearningmindset.com/books/)


<hr>

# <a name="schedule">Schedule</a>

Our schedule will be updated during the semesber. Please frequently check the schedule here.

| Dates | Presenters        | Topics                                                               | Suggested papers | Submissions                       |
|:-------:|-------------------||---------------------------------||-------------------------------------||:-----------------------------------:|
| 1/10  | Dr. Xiaoxiao Li | Couse Introduction <br> [Recording](https://ubc.zoom.us/rec/share/FbuuMyTp_KG8Xv8t2QnHh-dQdqaw2lAp1JXzuu--gF1BEUEDl3fk7yMjkLsYkPoH.y0KnStFcpMnZwPMv) <br> Password: %Ug4qW1+                                               |                  |            Signup Piazza                       | 
| 1/12  | Dr. Xiaoxiao Li | Introduction to computer vision <br>[slides](https://canvas.ubc.ca/courses/106862/files)                                      |      <img width=250/>            |  <img width=100/>            |
| 1/17  | Dr. Xiaoxiao Li | Introduction to deep learning<br>[slides](https://canvas.ubc.ca/courses/106862/files)                                        |                  |                                   |
| 1/19  | Dr. Xiaoxiao Li | Edge Detector <br>[slides](https://canvas.ubc.ca/courses/106862/files)                                                       |                  |                                   |
| **1/24**  | Luke <br><br> Ruichen             | **Presentation** – <br>  deep learning-based sketching                         |  Chan, C., Durand, F. and Isola, P., 2022. Learning to generate line drawings that convey geometry and semantics. <br> CVPR 2022 [paper](https://arxiv.org/pdf/2203.12691.pdf) <br> He, J., Zhang, S., Yang, M., Shan, Y. and Huang, T., 2019. Bi-directional cascade network for perceptual edge detection.  <br> CVPR 2019 [paper](https://arxiv.org/pdf/1902.10903.pdf)           | Submit review <br> Submit peer-grading [link](https://canvas.ubc.ca/courses/106862/assignments) |
| 1/26  | Dr. Xiaoxiao Li                  | Fileters and Multi-scale Representation                              |                  | Signup presentation  |
| 1/31  | Dr. Xiaoxiao Li | Image Classification I  <br> and Object Detection                      |                  |                                   |
| **2/2**   |    Danni, Hongrong [peer-review](https://arxiv.org/abs/2111.06377)    <br><br>   Yingrui, Yiming [peer-review](https://arxiv.org/abs/2111.06377)     | **Presentation** – <br>  Multi-scale image classification |  Huang, G., Chen, D., Li, T., Wu, F., Van Der Maaten, L. and Weinberger, K.Q., 2017. Multi-scale dense networks for resource efficient image classification. <br> ICLR 2018 [paper](https://arxiv.org/abs/1703.09844) <br> Pang, Y., Wang, T., Anwer, R.M., Khan, F.S. and Shao, L., 2019. Efficient featurized image pyramid network for single shot detector. <br> CVPR 2019 [paper](https://openaccess.thecvf.com/content_CVPR_2019/papers/Pang_Efficient_Featurized_Image_Pyramid_Network_for_Single_Shot_Detector_CVPR_2019_paper.pdf)               |  Submit review <br> Submit peer-grading           |
| 2/7   | Dr. Xiaoxiao Li |  Image Classification II – <br>  Practical Callenges                                 |                  |                                   |
| **2/9**   |    Larry, Weige [peer-review](https://arxiv.org/abs/2111.06377) <br><br> Mingyuan [peer-review](https://arxiv.org/abs/2111.06377)     |  **Presentation** – <br>  Advanced image classification | Li, J., Socher, R. and Hoi, S.C., 2020. Dividemix: Learning with noisy labels as semi-supervised learning. <br> ICLR 2020 [paper](https://arxiv.org/pdf/2002.07394.pdf)<br> Kang, J., Lee, S., Kim, N. and Kwak, S., 2022. Style Neophile: Constantly Seeking Novel Styles for Domain Generalization. <br> CVPR 2022 [paper](https://openaccess.thecvf.com/content/CVPR2022/papers/Kang_Style_Neophile_Constantly_Seeking_Novel_Styles_for_Domain_Generalization_CVPR_2022_paper.pdf)           |                                   |
| 2/14  | Dr. Xiaoxiao Li | Image Classification III   – <br> Trustworthiness                          |                  |                                   |
| **2/16**  |     Mohammad <br><br> Mingrui, Victor         | **Presentation** – <br>  Advanced image classification                         |  Doan, K.D., Lao, Y. and Li, P., 2022. Marksman Backdoor: Backdoor Attacks with Arbitrary Target Class. <br> NeurIPS 2022 [paper](https://arxiv.org/pdf/2210.09194.pdf)  <br>  Rigotti, M., Miksovic, C., Giurgiu, I., Gschwind, T. and Scotton, P., 2021, September. Attention-based Interpretability with Concept Transformers. <br> ICLR 2022 [paper](https://openreview.net/pdf?id=kAa9eDS0RdO) <br> Shao, Z., Bian, H., Chen, Y., Wang, Y., Zhang, J. and Ji, X., 2021. Transmil: Transformer based correlated multiple instance learning for whole slide image classification. NeurIPS 2021 [paper](https://arxiv.org/pdf/2106.00908.pdf)          |                                   |
| 2/24  |                   |                                                                      |                  | Submit project proposal           |
| 2/28  | Dr. Xiaoxiao Li | Vision-Transformer                                   |                  |                                   |
| **3/2**   |      Chunyu, Ali  <br><br>    Ningyuan, Jiahe     | **Presentation** – <br>  Vision Transformer           |  Ding, M., Xiao, B., Codella, N., Luo, P., Wang, J. and Yuan, L., 2022. DaViT: Dual Attention Vision Transformers. <br> ECCV 2022 [paper](https://arxiv.org/pdf/2204.03645.pdf)   <br>   Sun, T., Lu, C., Zhang, T. and Ling, H., 2022. Safe Self-Refinement for Transformer-based Domain Adaptation. <br> CVPR 2022 [paper](https://openaccess.thecvf.com/content/CVPR2022/papers/Sun_Safe_Self-Refinement_for_Transformer-Based_Domain_Adaptation_CVPR_2022_paper.pdf)         | Submit review <br> Submit peer-grading |
| 3/7   | TEA grad student  | Trustworthy AI                                                       |                  |                                   |
| 3/9   |  Dr. Fatemeh Dezaki <br> (Amazon) | Reasech topic in computer vision                                                       |                  |                                   |
| 3/14   | Dr. Xiaoxiao Li | Image Segmentation                                                   |                  | Submit review <br> Submit peer-grading |
| **3/16**  |     Chen, Weiya  <br><br>  Baichuan, Kevin        | **Presentation** – <br>  Advanced image segmentation                           |  Isensee, F., Jaeger, P.F., Kohl, S.A., Petersen, J. and Maier-Hein, K.H., 2021. nnU-Net: a self-configuring method for deep learning-based biomedical image segmentation.  <br>  Nature methods [paper](https://www.nature.com/articles/s41592-020-01008-z)  <br>  Ru, L., Zhan, Y., Yu, B. and Du, B., 2022. Learning Affinity from Attention: End-to-End Weakly-Supervised Semantic Segmentation with Transformers. <br> CVPR 2022 [paper](https://arxiv.org/abs/2203.02664)            |                                   |
| 3/21  | Dr. Xiaoxiao Li | Image Synthesis                                                      |                  |                                   |
| **3/23**  |      Beidi, Yilin  <br><br>     Christina    | **Presentation** – <br>  Advanced image synthesis                              | Park, T., Efros, A.A., Zhang, R. and Zhu, J.Y., 2020, August. Contrastive learning for unpaired image-to-image translation. <br> ECCV 2020 [paper](https://arxiv.org/pdf/2007.15651.pdf) <br> Chung, H., Sim, B., Ryu, D. and Ye, J.C., 2022. Improving Diffusion Models for Inverse Problems using Manifold Constraints. NeurIPS 2022 [paper](https://openreview.net/pdf?id=nJJjv0JDJju)      | Submit review <br> Submit peer-grading |
| 3/28  | Dr. Xiaoxiao Li <br> Bo Zhou (Yale) | Medical image registration and reconstruction                                                 |                  |  |
| **4/4**   |      Dong, Li    <br><br>   Jackson    | **Presentation** – <br>  Image registration                                    |   Chen, J., Frey, E.C., He, Y., Segars, W.P., Li, Y. and Du, Y., 2022. Balakrishnan, G., Zhao, A., Sabuncu, M.R., Guttag, J. and Dalca, A.V., 2019. VoxelMorph: a learning framework for deformable medical image registration. <br> IEEE TMI [paper](https://arxiv.org/pdf/1809.05231.pdf) <br>  Zhou, B., Schlemper, J., Dey, N., Salehi, S.S.M., Sheth, K., Liu, C., Duncan, J.S. and Sofka, M., 2022. Dual-domain self-supervised learning for accelerated non-Cartesian MRI reconstruction. <br> Medical Image Analysis [paper](https://www.sciencedirect.com/science/article/abs/pii/S1361841522001852)           |   Submit review <br> Submit peer-grading                                 |
| 4/6   | Dr. Xiaoxiao Li | Video Analysis                                                   |                  |                            |
| **4/11**  |   Ailar   <br><br>     Parsa       | **Presentation** – <br> Video Analysis                                     | Isobe, T., Li, S., Jia, X., Yuan, S., Slabaugh, G., Xu, C., Li, Y.L., Wang, S. and Tian, Q., 2020. Video super-resolution with temporal group attention. <br> CVPR 2022 [paper](https://openaccess.thecvf.com/content_CVPR_2020/papers/Isobe_Video_Super-Resolution_With_Temporal_Group_Attention_CVPR_2020_paper.pdf) <br> Dave, I.R., Chen, C. and Shah, M., 2022. SPAct: Self-supervised Privacy Preservation for Action Recognition. <br> CVPR 2022 [paper](https://openaccess.thecvf.com/content/CVPR2022/papers/Dave_SPAct_Self-Supervised_Privacy_Preservation_for_Action_Recognition_CVPR_2022_paper.pdf)                   | Submit review <br> Submit peer-grading |
| 4/21  | All students      | Final project                                                        |                  | Submit final project              |

<hr>

# Commitments
* It is my ultimate goal for this course, and my teaching, to develop your academic skills, supporting your future study and career. To do so will require commitments from <em>you and myself</em>  toward meeting this goal.
			

## Active Participation
* I will be prepared to use class time to help you understand the course material. I will respectfully listen to, understand, and answer questions asked in class. 
* You are expected to attend class and actively participate in discussions, answering questions, asking questions, presenting material, etc. Your participation will be respectful of your classmates, both of their opinions and of their current point in their educational journey, as we each approach the material with different backgrounds and contexts.

## Academic Integrity
* This course follows the rules presented in [Acdemic Integrity at UBC](https://academicintegrity.ubc.ca/).

## Learning Accomodation
* I will make this classroom an open and inclusive environment, accommodating many different learning styles and perspectives.
* Any student seeking accommodation in relation to a recognized disability should inform me at the beginning of the course.

## Physical and Mental Health
* I am willing to work with you individually when life goes off the rails.
* Coursework and college in general can become stressful and overwhelming, and your wellness can be impacted when you least expect it. You should participate in self-care and preventative measures, and be willing to find support when you need it. 
