# COMP90089_PROJECT
This is the group work of group 12 for the final project of COMP90089 2023.

The code is edited in colab and in the form of jupyter notebook. So it may be not easy to read it in github as the github does not show the guideline directory which can help you understand the logic of our code. If you want to read it easily, please download it and open it with colab.

There are two jupyter notebook in our work. The first one named by "data_extraction" is the code for extracting the patient cohort dataset from the MIMIC-IV. The second one is the machine learning code which we train our model on the extraced dataset.

We also provide the final pre-processed dataset that we finally work on. 

The digital phenotype that we use to find sepsis patients is as follows:

• Arterial hypotension (systolic blood pressure [SBP] < 90mmHg, mean arterial pressure [MAP]
< 70mmHg).

• Leucocytosis (white blood cell [WBC] count >12,000μL–1) or leukopenia (WBC count <4000μL−1).

• Thrombocytopenia (platelet count <100,000μL–1).

• Heart rate > 90 beats/min.

• Arterial hypoxemia (arterial oxygen tension [PaO2]/fraction of inspired oxygen [FiO2] <300).
