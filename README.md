<!-- -------------------------------------------------------------------------------- -->

<!-- Copyright 2024 Georgios Karagiannis -->

<!-- georgios.karagiannis@durham.ac.uk -->
<!-- Associate Professor -->
<!-- Department of Mathematical Sciences, Durham University, Durham,  UK  -->

<!-- This file is part of Spatio-Temporal_Statistics_Michaelmas_2025 -->
<!-- which is the material of the course -->
<!-- MATH4341: Spatio-Temporal Statistics -->
<!-- Epiphany term -->
<!-- taught by Georgios P. Katagiannis in the Department of Mathematical Sciences   -->
<!-- in the University of Durham  in Michaelmas term in 2025 -->

<!-- Spatio-Temporal_Statistics_Michaelmas_2025 is free software: -->
<!-- you can redistribute it and/or modify it-->
<!-- under the terms of the GNU General Public License as published by -->
<!-- the Free Software Foundation version 3 of the License. -->

<!-- Spatio-Temporal_Statistics_Michaelmas_2025 is distributed ->
<!-- in the hope that it will be useful, -->
<!-- but WITHOUT ANY WARRANTY; without even the implied warranty of -->
<!-- MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the -->
<!-- GNU General Public License for more details. -->

<!-- You should have received a copy of the GNU General Public License -->
<!-- along with Spatio-Temporal_Statistics_Michaelmas_2024 -->
<!-- If not, see <http://www.gnu.org/licenses/>. -->

<!-- -------------------------------------------------------------------------------- -->


------------------------------------------------------------------------

# Description

This repository contains the teaching material for the module ***MATH4331: Machine Learning and Neural Networks III*** in Epiphany term in 2025 @ Durham University.

- '[Description_sheet.pdf](./Description_sheet.pdf)' contains the ILOs, syllabus, and references  

Below you can find:  

+ [Lecture notes](./README.md#lecture-notes)  

+ [Computer lab notes](./README.md#computer-lab-notes)  

+ [Exercise sheets](./README.md#excercise-sheets-and-homework)  
<!--
+ [Practical computer based tests](https://github.com/georgios-stats/Machine_Learning_and_Neural_Networks_III_Epiphany_2025/blob/main/README.md#practical-first-computer-based-tests)  
-->

+ [Data sets](./README.md#data-sets)  

+ [Downloading instructions](./README.md#downloading-instructions)     

------------------------------------------------------------------------

# Lecture notes  

Lecture notes and lecture handouts are in folder **[[Lecture_notes]](./Lecture_notes)**  

#### Complete set of notes    

+ [PDF](./Lecture_notes/Lecture_notes_MLNN3.pdf)    

### Individual handouts

#### Learning  

Learning problem: Definitions, notation, and formulation -A recap  

+ Lecture notes [(PDF)](./Lecture_notes/01.Statistical_learning_framework_recap.pdf), [(HTML)](https://html-preview.github.io/?https://github.com/georgios-stats/Machine_Learning_and_Neural_Networks_III_Epiphany_2025/blob/main/Lecture_notes/01.Statistical_learning_framework_recap_xhtml/01.Statistical_learning_framework_recap.xhtml)  

Elements of convex learning problems  

+ Lecture notes [(PDF)](./Lecture_notes/02.Convex_learning_problems.pdf), [(HTML)](https://html-preview.github.io/?https://github.com/georgios-stats/Machine_Learning_and_Neural_Networks_III_Epiphany_2025/blob/main/Lecture_notes/02.Convex_learning_problems_xhtml/02.Convex_learning_problems.xhtml)  

Learnability and stability  

+ Lecture notes [(PDF)](./Lecture_notes/03.Learnability_and_stability.pdf), [(HTML)](https://html-preview.github.io/?https://github.com/georgios-stats/Machine_Learning_and_Neural_Networks_III_Epiphany_2025/blob/main/Lecture_notes/03.Learnability_and_stability_xhtml/03.Learnability_and_stability.xhtml)  

#### Training algorithms for machine learning      

+ Lecture notes [(PDF)](./Lecture_notes/04.Gradient_descent..pdf), [(HTML)](https://html-preview.github.io/?https://github.com/georgios-stats/Machine_Learning_and_Neural_Networks_III_Epiphany_2025/blob/main/Lecture_notes/04.Gradient_descent_xhtml/04.Gradient_descent.xhtml)  

Stochastic gradient descent  

+ Lecture notes [(PDF)](./Lecture_notes/05.Stochastic_gradient_descent.pdf), [(HTML)](https://html-preview.github.io/?https://github.com/georgios-stats/Machine_Learning_and_Neural_Networks_III_Epiphany_2025/blob/main/Lecture_notes/05.Stochastic_gradient_descent_xhtml/05.Stochastic_gradient_descent.xhtml)  

Stochastic gradient Langevin dynamics  

+ Lecture notes [(PDF)](./Lecture_notes/06.Stochastic_gradient_Langevine_dynamics.pdf), [(HTML)](https://html-preview.github.io/?https://github.com/georgios-stats/Machine_Learning_and_Neural_Networks_III_Epiphany_2025/blob/main/Lecture_notes/06.Stochastic_gradient_Langevine_dynamics_xhtml/06.Stochastic_gradient_Langevine_dynamics.xhtml)  

#### Models for supervised machine learning  

Support Vector Machines  

+ Lecture notes [(PDF)](./Lecture_notes/07.Support_Vector_Machines.pdf), [(HTML)](https://html-preview.github.io/?https://github.com/georgios-stats/Machine_Learning_and_Neural_Networks_III_Epiphany_2025/blob/main/Lecture_notes/07.Support_Vector_Machines_xhtml/07.Support_Vector_Machines.xhtml)  

Kernel methods (extensions to non linear feature spaces)  

+ Lecture notes [(PDF)](./Lecture_notes/08.Kernel_Methods.pdf), [(HTML)](https://html-preview.github.io/?https://github.com/georgios-stats/Machine_Learning_and_Neural_Networks_III_Epiphany_2025/blob/main/Lecture_notes/08.Kernel_Methods_xhtml/08.Kernel_Methods.xhtml)  

Multiclass_classification (extensions to many classes)    

+ Lecture notes [(PDF)](./Lecture_notes/09.Multiclass_classification.pdf), [(HTML)](https://html-preview.github.io/?https://github.com/georgios-stats/Machine_Learning_and_Neural_Networks_III_Epiphany_2025/blob/main/Lecture_notes/09.Multiclass_classification_xhtml/09.Multiclass_classification.xhtml)  

Artificial Neural Networks (application to feature space extensions)  

+ Lecture notes [(PDF)](./Lecture_notes/10.Artificial_neural_networks.pdf), [(HTML)](https://html-preview.github.io/?https://github.com/georgios-stats/Machine_Learning_and_Neural_Networks_III_Epiphany_2025/blob/main/Lecture_notes/10.Artificial_neural_networks_xhtml/10.Artificial_neural_networks.xhtml)  

Gaussian process regression (application of kernel trick/methods)  

+ Lecture notes [(PDF)](./Lecture_notes/10.Artificial_neural_networks.pdf), [(HTML)](https://html-preview.github.io/?https://github.com/georgios-stats/Machine_Learning_and_Neural_Networks_III_Epiphany_2025/blob/main/Lecture_notes/11.Gaussian_process_regression_xhtml/11.Gaussian_process_regression.xhtml)  

------------------------------------------------------------------------

# Computer lab notes  

#### Technical specs  

The computer lab notes run by software whose version is the same as that installed in the CIS server [anywhereapp](https://appsanywhere.durham.ac.uk). I.e.  

64 bit version of  

+ RStudio (2024.04.2) for [Linux, MS Windows, or MacOS](https://dailies.rstudio.com/version/2024.04.2+764.pro1/?_gl=1*np68ei*_ga*NjQzMzkxMjU0LjE3Mjk0MjU3NDM.*_ga_2C0WZ1JHG0*MTcyOTk3ODkwMC4zLjEuMTcyOTk3ODk2NC4wLjAuMA..)  

+ R version 4.4.1 for [Linux](https://cran.r-project.org/src/base/R-4/R-4.4.1.tar.gz), [MS Windows](https://cran.r-project.org/bin/windows/base/R-4.4.1-win.exe), or [MacOS](https://cran.r-project.org/bin/macosx/big-sur-arm64/base/R-4.4.1-arm64.pkg)  

+ RTools 4.40: for  [MS Windows](https://cran.r-project.org/bin/macosx/big-sur-arm64/base/R-4.4.1-arm64.pkg)  

Required R packages are     

    install.packages(pkgs = c( 
        "nloptr", "numDeriv", 
        "knitr", "mvtnorm", "e1071", "nnet", 
        "faraway"
        ) )  


#### Lab 1:   

... Not available yet          

<!--

Tasks: [View (HTML)](https://html-preview.github.io/?url=https://github.com/georgios-stats/Machine_Learning_and_Neural_Networks_III_Epiphany_2025/blob/main/Computer_lab_notes/Spatial_data_in_R_tasks.html) ; [Download (HTML)](https://raw.githubusercontent.com/georgios-stats/Spatio-Temporal_Statistics_Michaelmas_2024/refs/heads/main/Computer_lab_notes/Spatial_data_in_R_tasks.html)  

Complete: [View (HTML)](https://html-preview.github.io/?url=https://github.com/georgios-stats/Machine_Learning_and_Neural_Networks_III_Epiphany_2025/blob/main/Computer_lab_notes/Spatial_data_in_R_complete.html) ; [Download (HTML)](https://raw.githubusercontent.com/georgios-stats/Spatio-Temporal_Statistics_Michaelmas_2024/refs/heads/main/Computer_lab_notes/Spatial_data_in_R_complete.html)  
-->

#### Lab 2:             

... Not available yet  

<!--
This is about the fiting (cross-)semivariograms, implementing (co-)Kriging, and implementind the linear model of coregionalization.  

Tasks: [View (HTML)](https://html-preview.github.io/?url=https://github.com/georgios-stats/Machine_Learning_and_Neural_Networks_III_Epiphany_2025/blob/main/Computer_lab_notes/Point_referenced_spatial_data_modelling_tasks.html)  ; [Download (HTML)](https://raw.githubusercontent.com/georgios-stats/Spatio-Temporal_Statistics_Michaelmas_2024/refs/heads/main/Computer_lab_notes/Point_referenced_spatial_data_modelling_tasks.html)  

Complete: [View (HTML)](https://html-preview.github.io/?url=https://github.com/georgios-stats/Machine_Learning_and_Neural_Networks_III_Epiphany_2025/blob/main/Computer_lab_notes/Point_referenced_spatial_data_modelling_complete.html) ; [Download (HTML)](https://raw.githubusercontent.com/georgios-stats/Spatio-Temporal_Statistics_Michaelmas_2024/refs/heads/main/Computer_lab_notes/Point_referenced_spatial_data_modelling_complete.html)  
-->

#### Lab 3:          

... Not available yet     

<!--
This is about design neighborhoods, proximity matrices, (global and local) Moran's tests, Simultaneous Auto-regressive (SAR) model fitting, and Conditional Auto-Regressive (CAR) model fitting.  

Tasks: [View (HTML)](https://html-preview.github.io/?url=https://github.com/georgios-stats/Machine_Learning_and_Neural_Networks_III_Epiphany_2025/blob/main/Computer_lab_notes/Aerial_unit_spatial_data_modelling_tasks.html) ; [Download (HTML)](https://raw.githubusercontent.com/georgios-stats/Spatio-Temporal_Statistics_Michaelmas_2024/refs/heads/main/Computer_lab_notes/Aerial_unit_spatial_data_modelling_tasks.html)  

Complete [View (HTML)](https://html-preview.github.io/?url=https://github.com/georgios-stats/Machine_Learning_and_Neural_Networks_III_Epiphany_2025/blob/main/Computer_lab_notes/Aerial_unit_spatial_data_modelling_complete.html) ; [Download (HTML)](https://raw.githubusercontent.com/georgios-stats/Spatio-Temporal_Statistics_Michaelmas_2024/refs/heads/main/Computer_lab_notes/Aerial_unit_spatial_data_modelling_complete.html)  
-->

#### Lab 4:      

... Not available yet  

------------------------------------------------------------------------

# Exercise sheets and homework 

#### Exercise sheet  

+ [Problems only (PDF)](./Exercise_sheets/Exercise_sheet_questions.pdf)  

+ [Problems only (HTML)](https://html-preview.github.io/?url=https://github.com/georgios-stats/Machine_Learning_and_Neural_Networks_III_Epiphany_2025/blob/main/Exercise_sheets/Exercise_sheet_complete_xhtml/Exercise_sheet_questions.xhtml)  

+ [Problems and solutions (PDF)](./Exercise_sheets/Exercise_sheet_complete.pdf)  

+ [Problems and solutions (HTML)](https://html-preview.github.io/?url=https://github.com/georgios-stats/Machine_Learning_and_Neural_Networks_III_Epiphany_2025/blob/main/Exercise_sheets/Exercise_sheet_complete_xhtml/Exercise_sheet_complete.xhtml)  

#### Homework 1  

+ [Problems only (PDF)](./Exercise_sheets/Homework_sheet_1_questions.pdf)  

+ [Problems only (HTML)](https://html-preview.github.io/?url=https://github.com/georgios-stats/Machine_Learning_and_Neural_Networks_III_Epiphany_2025/blob/main/Exercise_sheets/Homework_sheet_1_complete_xhtml/Homework_sheet_1_questions.xhtml)  

+ [Problems and solutions (PDF)](./Exercise_sheets/Homework_sheet_1_complete.pdf)  

+ [Problems and solutions (HTML)](https://html-preview.github.io/?url=https://github.com/georgios-stats/Machine_Learning_and_Neural_Networks_III_Epiphany_2025/blob/main/Exercise_sheets/Homework_sheet_1_complete_xhtml/Homework_sheet_1_complete.xhtml)  

#### Homework 2  

... Not available yet  

<!--
+ [Problems only (PDF)](./Exercise_sheets/Homework_sheet_2_questions.pdf)  

+ [Problems only (HTML)](https://html-preview.github.io/?url=https://github.com/georgios-stats/Machine_Learning_and_Neural_Networks_III_Epiphany_2025/blob/main/Exercise_sheets/Homework_sheet_2_complete_xhtml/Homework_sheet_2_questions.xhtml)  

+ [Problems and solutions (PDF)](./Exercise_sheets/Homework_sheet_2_complete.pdf)  

+ [Problems and solutions (HTML)](https://html-preview.github.io/?url=https://github.com/georgios-stats/Machine_Learning_and_Neural_Networks_III_Epiphany_2025/blob/main/Exercise_sheets/Homework_sheet_2_complete_xhtml/Homework_sheet_2_complete.xhtml)    
-->

#### Homework 3  

... Not available yet  

<!--
+ [Problems only (PDF)](./Exercise_sheets/Homework_sheet_3_questions.pdf)  

+ [Problems only (HTML)](https://html-preview.github.io/?url=https://github.com/georgios-stats/Machine_Learning_and_Neural_Networks_III_Epiphany_2025/blob/main/Exercise_sheets/Homework_sheet_3_complete_xhtml/Homework_sheet_3_questions.xhtml)  

+ [Problems and solutions (PDF)](./Exercise_sheets/Homework_sheet_3_complete.pdf)  

+ [Problems and solutions (HTML)](https://html-preview.github.io/?url=https://github.com/georgios-stats/Machine_Learning_and_Neural_Networks_III_Epiphany_2025/blob/main/Exercise_sheets/Homework_sheet_3_complete_xhtml/Homework_sheet_3_complete.xhtml)  
-->

#### Homework 4  

... Not available yet  

<!--
+ [Problems only (PDF)](./Exercise_sheets/Homework_sheet_4_questions.pdf)  

+ [Problems only (HTML)](https://html-preview.github.io/?url=https://github.com/georgios-stats/Machine_Learning_and_Neural_Networks_III_Epiphany_2025/blob/main/Exercise_sheets/Homework_sheet_4_complete_xhtml/Homework_sheet_4_questions.xhtml)  

+ [Problems and solutions (PDF)](./Exercise_sheets/Homework_sheet_4_complete.pdf)  

+ [Problems and solutions (HTML)](https://html-preview.github.io/?url=https://github.com/georgios-stats/Machine_Learning_and_Neural_Networks_III_Epiphany_2025/blob/main/Exercise_sheets/Homework_sheet_4_complete_xhtml/Homework_sheet_4_complete.xhtml)  
-->


#### Revision  

... Not available yet  

<!--
+ [View (PDF)](./Exercise_sheets/Revision_sheet.pdf)  

+ [View (HTML)](https://html-preview.github.io/?url=https://github.com/georgios-stats/Machine_Learning_and_Neural_Networks_III_Epiphany_2025/blob/main/Exercise_sheets/Revision_sheet_xhtml/Revision_sheet.xhtml)  
-->

------------------------------------------------------------------------  

# Practical Tests  

#### Practical First Computer Based Test

#### Practical First Computer Based Test  

... Not available yet  

<!--

Solutions only  

+ [Spatial data (HTML)](https://html-preview.github.io/?url=https://github.com/georgios-stats/Machine_Learning_and_Neural_Networks_III_Epiphany_2025/blob/main/Exercise_sheets/FPCBT-Topic-Spatial-data.html)    

+ [Geostatistical data (HTML)](https://html-preview.github.io/?url=https://github.com/georgios-stats/Machine_Learning_and_Neural_Networks_III_Epiphany_2025/blob/main/Exercise_sheets/FPCBT-Topic-Geostatistical-data.html)        

+ [Aerial unit data (HTML)](https://html-preview.github.io/?url=https://github.com/georgios-stats/Machine_Learning_and_Neural_Networks_III_Epiphany_2025/blob/main/Exercise_sheets/FPCBT-Topic-Aerial-unit-data.html)    
-->

------------------------------------------------------------------------

# Downloading instructions     

### How to download the whole repository

Ways:

1. You can click [[HERE](https://github.com/georgios-stats/Machine_Learning_and_Neural_Networks_III_Epiphany_2025/archive/refs/heads/main.zip)].

2. You can click the green button 'Clone or download' and download it as a zip file

3. You can use the program 'git' (<https://git-scm.com/>):
    
    -   in windows/linux: 
    
        download and install git from https://git-scm.com/
    
    -   in Debian linux run in the terminal: 
    
        sudo apt-get install git
    
    -   in Red Hat linux run in the terminal: 
    
        sudo yum install git
    
    ... then run:

    -   git clone https://github.com/georgios-stats/Machine_Learning_and_Neural_Networks_III_Epiphany_2025.git

4. You can use rstudio:

    1.  Go to File &gt; New Project &gt; Version Control &gt; Git
    
    2.  In the section *Repository URL* write
        
        -   <https://github.com/georgios-stats/Machine_Learning_and_Neural_Networks_III_Epiphany_2025.git>
        
        -   … and complete the rest as you wish
    
    3.  Hit *Create a Project*

### How to download a specific file

Ways:

1. You can just navigate to the file from the browser and download it.

2. You can use the GitZip add-on for Firefox available [HERE](https://www.google.com/url?sa=t&rct=j&q=&esrc=s&source=web&cd=3&cad=rja&uact=8&ved=2ahUKEwias52xjd3nAhXPUs0KHeXHCEUQFjACegQIAhAB&url=https%3A%2F%2Faddons.mozilla.org%2Fen-US%2Ffirefox%2Faddon%2Fgitzip%2F&usg=AOvVaw37servrJ29tuNcx9dIQDqy) or the Chrome add-on GitZip available [HERE](https://www.google.com/url?sa=t&rct=j&q=&esrc=s&source=web&cd=2&cad=rja&uact=8&ved=2ahUKEwias52xjd3nAhXPUs0KHeXHCEUQFjABegQIARAB&url=https%3A%2F%2Fchrome.google.com%2Fwebstore%2Fdetail%2Fgitzip-for-github%2Fffabmkklhbepgcgfonabamgnfafbdlkn%3Fhl%3Den&usg=AOvVaw1Pn3VXuXz1Fphl7dsPEhDS)

------------------------------------------------------------------------

