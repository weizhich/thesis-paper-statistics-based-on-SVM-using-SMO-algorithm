# Paper Statistics Based on SVM using SMO Algorithm
* This is my private research for bachelor degree of science in computer science.
* Instructed by Professor Jian Wu in Advanced Computing and System Laboratory, Zhejiang University.
## Abstract
This paper focuses on study of identifying handwritten characters, and the implementation of student papers Identification and Management System. Character recognition is important for the establishment of digital paper management system. How quickly and accurately can the system extract the teacher's grading information, identify and statistics papers is one crucial step of the work of paper identification and management. It is difficult to recognize handwritten characters, due to diverse handwriting style which is hard to standardize. In addition, the process of handwriting recognition is easily disturbed by noise. What’s more, the correctness required by a paper system is strict. Currently a variety of domestic and aboard handwriting recognition is still located in the stage of development, such as handwriting recognition based on neural network; stroke-based analysis of handwriting recognition. Recognition results are often unsatisfactory. It is difficult to achieve a high degree of accuracy required in the paper system. Offline handwriting recognition is even lower. And the current study does not recognize the handwriting marking symbol, the majority of the research is to identify the handwriting of numbers and letters. It is necessary to design new research programs which is based on traditional handwriting recognition. So work in this paper has a certain research and application values.
Specific work and the advantages of this paper are: 
* Based on the study of traditional handwritten digital feature, design a variety of feature extraction methods for correct mark√and wrong mark×. 
* Extract 102 dimensions feature vector from numerous samples, which works well. The sample space is almost linearly separable. The result of classification is good even for the linearly classifier. 
* Construct SVM classifier using SMO algorithm.
* Through numerous samples, choose the best kernel function. And select the best parameters using grid-search and cross-variation. According the test result, the classifier shows good performance. It can reach 100% correctness with 100 real samples.
* Construct student paper recognition and management system. It can recognize paper, count information, show contents by each problem, save and retrieve paper.
## Keywords
* Image Preprocessing
* Paper Management
* Handwritten Character Recognition
* Support Vector Machine
* SMO
* Feature Extraction
* Kernel Function
* Optimal Parameter Selection 
