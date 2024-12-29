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
* Piazza: [https://piazza.com/ubc.ca/winterterm22024/eece570](https://piazza.com/ubc.ca/winterterm22024/eece570)

{% include resources.html content=site.goals %}

## <a name="contact">Contacts</a>
* Instructor: Dr. Xiaoxiao Li (xiaoxiao.li@ece.ubc.ca)
* TA: Zhao Chen () and Jane Shi ()
* Email: include ‘[EECE 570]’ in the subject.

{% include resources.html content=site.resources %}

## <a name="time-and-location">Time and Location</a>

* Location:
Mon/Wed ∥ 9:30 – 11:00 ∥ DMP-Floor 2-Room 201
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

<style>
/* Table style */
table {
  border-collapse: collapse; /* Combine borders to avoid double lines */
  width: 100%; /* Make the table responsive to the container */
}

th, td {
  border: 1px solid black; /* Add borders around cells */
  padding: 8px; /* Add padding inside cells for better readability */
  text-align: left; /* Align text to the left */
}

th {
  background-color: #f2f2f2; /* Light gray background for table headers */
  font-weight: bold; /* Make headers bold */
}
</style>

<h1><a name="schedule">Schedule</a></h1>

<p>
Our schedule will be updated during the semester. Please frequently check the schedule here.
</p>


| Dates | Presenters        | Topics                                                               | Suggested papers | Submissions                       |
|:-------:|-------------------||---------------------------------||-------------------------------------||:-----------------------------------:|
| 1/6  | Dr. Xiaoxiao Li | Course Introduction                                           |                  |            Signup Piazza                       | 
| 1/8  | Dr. Xiaoxiao Li | Watching Video <br> [History of Computer Vision](https://www.youtube.com/watch?v=hCewSTTOt_4) <br>                                     |      <img width=250/>            |  <img width=100/>            |
| 1/13  | Dr. Xiaoxiao Li | Computer Vision Foundations          |                  |      （9:35-10:00）Signup presentation      |
| 1/15  | Dr. Xiaoxiao Li | Introduction to Deep Learning         |                  |              |
| 1/20  | Dr. Xiaoxiao Li | Supervised Image Analysis                |  |  |
| 1/22  | Dr. Xiaoxiao Li | Unsupervised Image Analysis                 |                  |                                  |
| 1/27  | Dr. Xiaoxiao Li | Introduction to Medical Image Analysis       |                 |                  |
| 1/29  | Dr. Xiaoxiao Li | Neuroimaging and Pathology Image Analysis    |                  |                           |
| **2/3**   |  xxx   <br> [peer-review]() <br>  xxx  <br> [peer-review]() | **Presentation** – <br> Medical Image Analysis | xxxx <br> CVPR xxxx [paper]() <br> xxxx <br> ICLR xxxx [paper]()|  Submit review <br> Submit peer-grading           |
| 2/5  |  Dr. Xiaoxiao Li | Vision Foundation Models   |  |  |
| **2/10**   |  xxx   <br> [peer-review]() <br>  xxx  <br> [peer-review]() | **Presentation** – <br> Vision Foundation Models | xxxx <br> CVPR xxxx [paper]() <br> xxxx <br> ICLR xxxx [paper]()|  Submit review <br> Submit peer-grading           |
| 2/12  | Invited Talk | TBD                    |                  |                                   |
| 2/24  | Dr. Xiaoxiao Li | Vision Language Modeling 1                    |  
| 2/26  | Dr. Xiaoxiao Li | Vision Language Modeling 2                    |                  |                                   |
|**3/3** | xxx   <br> [peer-review]() <br>  xxx  <br> [peer-review]() | **Presentation** – <br> Vision Language Modeling | xxxx <br> CVPR xxxx [paper]() <br> xxxx <br> ICLR xxxx [paper]()|  Submit review <br> Submit peer-grading           |
|**3/5** | xxx   <br> [peer-review]() <br>  xxx  <br> [peer-review]() | **Presentation** – <br> Vision Language Modeling | xxxx <br> CVPR xxxx [paper]() <br> xxxx <br> ICLR xxxx [paper]()|  Submit review <br> Submit peer-grading           |
| 3/10  | Dr. Xiaoxiao Li | Image Generative Models                    |                  |                                   |
|**3/12** | xxx   <br> [peer-review]() <br>  xxx  <br> [peer-review]() | **Presentation** – <br> Image Generative Models | xxxx <br> CVPR xxxx [paper]() <br> xxxx <br> ICLR xxxx [paper]()|  Submit review <br> Submit peer-grading        |                 |       
|**3/17** | xxx   <br> [peer-review]() <br>  xxx  <br> [peer-review]() | **Presentation** – <br> Text-to-image Generation | xxxx <br> CVPR xxxx [paper]() <br> xxxx <br> ICLR xxxx [paper]()|  Submit review <br> Submit peer-grading           |
| 3/19  | Dr. Xiaoxiao Li | Vision Prompt Tuning                    |                  |                                   |
|**3/24** | xxx   <br> [peer-review]() <br>  xxx  <br> [peer-review]() | **Presentation** – <br> Vision Prompt Tuning | Visual Programming: Compositional visual reasoning without training <br> CVPR 2023 [paper](https://arxiv.org/pdf/2211.11559) <br> E^2VPT: An Effective and Efficient Approach for Visual Prompt Tuning <br> ICCV 2023 [paper](https://openaccess.thecvf.com/content/ICCV2023/papers/Han_E2VPT_An_Effective_and_Efficient_Approach_for_Visual_Prompt_Tuning_ICCV_2023_paper.pdf)|  Submit review <br> Submit peer-grading           |
| 3/26  | Dr. Xiaoxiao Li | Robustness for Vision Tasks                    |                  |                                   |
|**3/31** | xxx   <br> [peer-review]() <br>  xxx  <br> [peer-review]() | **Presentation** – <br> Robustness for Vision Tasks  | Attack To Defend: Exploiting Adversarial Attacks for Detecting Poisoned Models <br> CVPR 2024 [paper](https://openaccess.thecvf.com/content/CVPR2024/papers/Fares_Attack_To_Defend_Exploiting_Adversarial_Attacks_for_Detecting_Poisoned_Models_CVPR_2024_paper.pdf) <br>Strong Transferable Adversarial Attacks via Ensembled Asymptotically Normal Distribution Learning <br> CVPR 2024 [paper](https://arxiv.org/pdf/2411.07231v1)|  Submit review <br> Submit peer-grading           |
| 4/2  | Dr. Xuandong Zhao | Image Watermakt                  |                  |                                   |
| **4/7**  |  xxx   <br> [peer-review]() <br>  xxx  <br> [peer-review]() | **Presentation** – <br> Image Watermark | Attack-Resilient Image Watermarking Using Stable Diffusion <br> NeurIPS 2024 [paper](https://openreview.net/pdf?id=e6KrSouGHJ) <br>ProMark: Proactive Diffusion Watermarking for Causal Attribution <br> CVPR 2024 [paper](https://openaccess.thecvf.com/content/CVPR2024/papers/Asnani_ProMark_Proactive_Diffusion_Watermarking_for_Causal_Attribution_CVPR_2024_paper.pdf)|  Submit review <br> Submit peer-grading           |
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
