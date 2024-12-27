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
* Piazza: [https://piazza.com/ubc.ca/winterterm22023/eece570](https://piazza.com/ubc.ca/winterterm22023/eece570)

{% include resources.html content=site.goals %}

## <a name="contact">Contacts</a>
* Instructor: Dr. Xiaoxiao Li (xiaoxiao.li@ece.ubc.ca)
* TA: Beidi Zhao (beidiz@student.ubc.ca)
* Email: include ‘[EECE 570]’ in the subject.

{% include resources.html content=site.resources %}

## <a name="time-and-location">Time and Location</a>

* Location:
Mon/Wed ∥ 9:30 – 11:00 ∥ Food, Nutrition and Health 30
* TA Office Hours: TBA
* Instructor Office Hours: Weds 15:00-16:00 (by appointment only)

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
| 1/8  | Dr. Xiaoxiao Li | Course Introduction                                           |                  |            Signup Piazza                       | 
| 1/10  | Dr. Xiaoxiao Li | Introduction to general computer vision                                     |      <img width=250/>            |  <img width=100/>            |
| 1/15  | Dr. Xiaoxiao Li | Introduction to deep learning                                       |                  |                                   |
| 1/17  | Dr. Zongwei Zhou (JHU) | Medical Imaging: dataset, annotation, and algorithm         |                  |              （9:35-10:00）Signup presentation                     |
| 1/22  | Dr. Xiaoxiao Li | Feature Learning Techniques  (online)                 |  |  |
| 1/24  | Dr. Xiaoxiao Li | Introduction to federated learning                                                      |                  |                                   |
| 1/29  | Dr. Xiaoxiao Li & Meirui Jiang (CUHK) | Image Classification on Imperfect Data                      |                  |                                   |
| 1/31  | Dr. Xiaofeng Liu (Harvard) | Generalizable Deep Learning for Medical Image Analysis                    |                  |                                   |
| **2/2**   |     Ali and Elahe  <br> [peer-review](https://forms.gle/DL9TttL1WUK58ss76) <br>   Obed  <br> [peer-review](https://forms.gle/L2a98VCLVhRrxBQS7) | **Presentation** – <br> Domain Adaptation and Generalization | Visualizing Adapted Knowledge in Domain Transfer. <br> CVPR 2021 [paper](https://arxiv.org/abs/2104.10602) <br> Sparse Mixture-of-Experts are Domain Generalizable Learners <br> ICLR 2023 [paper](https://openreview.net/pdf?id=RecZ9nB9Q4)|  Submit review <br> Submit peer-grading           |
| **2/5**   | Kevin and Michael  <br> [peer-review](https://forms.gle/6oFL3CsaRNve4ALX9) <br>   Zhiwei and Zichen  <br> [peer-review](https://forms.gle/mPsCYLHmiWuPmiZQA)  | **Presentation** – <br> Semi-supervised Learning    | FreeMatch: Self-adaptive Thresholding for Semi-supervised Learning <br> ICLR 2023 [paper](https://arxiv.org/abs/2205.07246) <br> Unsupervised Selective Labeling for More Effective Semi-Supervised Learning <br> ECCV 2022 [paper](https://arxiv.org/abs/2110.03006)|  Submit review <br> Submit peer-grading           |
| 2/7   | Dr. Mengwei Ren (NYU) | TBA |                  |  
| **2/12**   | AmirHossein and Jiaxun <br> [peer-review](https://forms.gle/jgdpAMcnUQYXhrmHA) <br> Crystal and Congzhen <br> [peer-review](https://forms.gle/aiBKmrd7sZApLo4b6)   | **Presentation** – <br> Self-supervised Learning   | Masked siamese networks for label-efficient learning  <br> ECCV 2022 [paper](https://arxiv.org/pdf/2204.07141.pdf) <br> Masked autoencoders are scalable vision learners <br> CVPR 2022 [paper](https://openaccess.thecvf.com/content/CVPR2022/papers/He_Masked_Autoencoders_Are_Scalable_Vision_Learners_CVPR_2022_paper.pdf) |  Submit review <br> Submit peer-grading           |
| 2/14  | Dr. Xiaoxiao Li & Yangsibo Huang (Princeton)| Image Classification III   – <br> Pitfalls                  |                  |                                   |
| **2/26**  |             |                                                                      |                  | Submit project proposal           |
| 2/26  | Dr. Xiaoxiao Li | Presentation at AAAI - Deployable AI |                  |                                   |
| **2/28**  |    Harsh <br> [peer-review](https://forms.gle/m6Suwm9b4TAzVYVi9) <br> Haoran and Poppy <br> [peer-review](https://forms.gle/Aquob4KhV4TACWnBA) |  **Presentation** – <br>  Backdoor Attacks in CV   | Neurotoxin: Durable Backdoors in Federated Learning <br> ICML 2022 [paper](https://proceedings.mlr.press/v162/zhang22w/zhang22w.pdf) <br> How to Backdoor Diffusion Models? <br> CVPR 2023 [paper](https://openaccess.thecvf.com/content/CVPR2023/papers/Chou_How_to_Backdoor_Diffusion_Models_CVPR_2023_paper.pdf) | Submit review <br> Submit peer-grading |           
| 3/4  | Dr. Xiaoxiao Li | Vision-Transformer                                   |                  |                                   |
| **3/6**   | Milad and Pooria  <br> [peer-review](https://forms.gle/Y8YLa5EkSuFAc7eG7) <br> Forrest and Maissan <br> [peer-review](https://forms.gle/CyyFsndvzTp275rDA) |   **Presentation** – <br>  ViT (sigle modality)   |CRATE: Emergence of Segmentation with Minimalistic White-Box Transformers <br> CPAL 2024 [paper](https://arxiv.org/pdf/2308.16271.pdf) <br> Scaling Vision Transformers to 22 Billion Parameters <br> ICML 2023 [paper](https://proceedings.mlr.press/v202/dehghani23a/dehghani23a.pdf) |  Submit review <br> Submit peer-grading           |
| **3/11**   |     Howie and Xiaofan  <br> [peer-review](https://forms.gle/B5p6ZhgUMUCV7vY26) <br> Yishen and Chris <br> [peer-review](https://forms.gle/LK746KeVh9FUvcVc6) |  **Presentation** – <br>  ViT (text-image)    |CLIPPO: Image-and-Language Understanding From Pixels Only  <br> CVPR 2023 [paper](https://openaccess.thecvf.com/content/CVPR2023/papers/Tschannen_CLIPPO_Image-and-Language_Understanding_From_Pixels_Only_CVPR_2023_paper.pdf) <br> Blip: Bootstrapping language-image pre-training for unified vision-language understanding and generation <br> ICML 2022 [paper](https://proceedings.mlr.press/v162/li22n/li22n.pdf)|  Submit review <br> Submit peer-grading      |
| 3/13  | Dr. SangMook Kim & Beidi Zhao| Pathology Image Analysis                                                   |                  |                            |
| **3/18**  |   Tarek and Baraa  <br> [peer-review](https://forms.gle/LrMQURZ1WiX8a3cF6) <br> Nima and Bahar <br> [peer-review](https://forms.gle/q3c6e6SavrtUJwCn6) |  **Presentation** – <br>  Pathology Image Analysis  | TransMIL: Transformer based Correlated Multiple Instance Learning for Whole Slide Image Classification <br> NeurIPS 2021 [paper](https://proceedings.neurips.cc/paper_files/paper/2021/file/10c272d06794d3e5785d5e7c5356e9ff-Paper.pdf) <br> Scaling Vision Transformers to Gigapixel Images via Hierarchical Self-Supervised Learning <br> CVPR 2022 [paper](https://openaccess.thecvf.com/content/CVPR2022/papers/Chen_Scaling_Vision_Transformers_to_Gigapixel_Images_via_Hierarchical_Self-Supervised_Learning_CVPR_2022_paper.pdf) |  Submit review <br> Submit peer-grading           |
| 3/20   | Dr. Xiaoxiao Li  | Dream and Distillation                                                  |                  |  |
| **3/25**  | Sara and Xinyu  <br> [peer-review](https://forms.gle/2eehtURVofaorpUZ6) <br> Avneet and Zizhou <br> [peer-review](https://forms.gle/UyQPLW3Rx56KFVAf8) | **Presentation** – <br>  Advanced Dataset Distillation and Their Applications    | Scaling up dataset distillation to imagenet-1k with constant memory <br> ICML 2023 [paper](https://proceedings.mlr.press/v202/cui23e/cui23e.pdf) <br> DataDAM: Efficient Dataset Distillation with Attention Matching <br> ICCV 2023 [paper](https://openaccess.thecvf.com/content/ICCV2023/papers/Sajedi_DataDAM_Efficient_Dataset_Distillation_with_Attention_Matching_ICCV_2023_paper.pdf)  |  Submit review <br> Submit peer-grading           |
| 3/27  | Dr. Xiaoxiao Li | Image Synthesis                                                      |                  |                                   |
| **4/3**  |  Akhil  <br> [peer-review](https://forms.gle/3iXx6DjnNAjbQPQJ6) <br> Yanting and Chen <br> [peer-review](https://forms.gle/s9QrnscQdj3M4tcX6) |  **Presentation** – <br>  Diffusion Models    | Diffusion Autoencoders: Toward a Meaningful and Decodable Representation <br> CVPR 2022 [paper](http://arxiv.org/abs/2111.15640) <br> Adding Conditional Control to Text-to-Image Diffusion Models <br> ICCV 2023 [paper](https://arxiv.org/abs/2302.05543) |  Submit review <br> Submit peer-grading           |
| 4/8  | Dr. Jun Ma (UoT)  | Advanced Medical Image Segmentation                                                 |                  |  |                                |
| **4/10**  | Alireza and Tianyi  <br> [peer-review](https://forms.gle/L9KcnxjejMaVCqVU8) <br> Wen <br> [peer-review](https://forms.gle/ESBzXLUjCnTMsuPf6) |  **Presentation** – <br>  Medical Image Segmentation with Foundation Models   |CLIP-Driven Universal Model for Organ Segmentation and Tumor Detection <br> ICCV 2023 [paper](https://openaccess.thecvf.com/content/ICCV2023/papers/Liu_CLIP-Driven_Universal_Model_for_Organ_Segmentation_and_Tumor_Detection_ICCV_2023_paper.pdf) <br> Continual Segment: Towards a Single, Unified and Non-forgetting Continual Segmentation Model of 143 Whole-body Organs in CT Scans <br> ICCV 2023 [paper](https://openaccess.thecvf.com/content/ICCV2023/papers/Ji_Continual_Segment_Towards_a_Single_Unified_and_Non-forgetting_Continual_Segmentation_ICCV_2023_paper.pdf)   |  Submit review <br> Submit peer-grading           |
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
