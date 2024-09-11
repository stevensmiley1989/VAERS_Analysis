# VAERS_Analysis
DTSA_5509_Final

## 1 Jupyter Notebook<a class="anchor" id="1"></a>
Links below to visualize the notebooks rendered.

| Notebook | Description |
|--------------------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| [DTSA_5509_Final_Part1_of_2.ipynb](https://nbviewer.org/github/stevensmiley1989/VAERS_Analysis/blob/main/DTSA_5509_Final_Part1_of_2.ipynb) | Part 1 of 2 |
|  [DTSA_5509_Final_Part2_of_2.ipynb](https://nbviewer.org/github/stevensmiley1989/VAERS_Analysis/blob/main/DTSA_5509_Final_Part2_of_2.ipynb) | Part 2 of 2 |


## 2 Data Inputs <a class="anchor" id="2"></a>
**Dataset**: “VAERS Data Sets”

**Dataset Source**: https://vaers.hhs.gov/data/datasets.html

**Key attributes/dimensions of the data**: 
There are 3 main CSV files associated with this dataset:
1)	*VAERSDATA.csv 
2)	*VAERSSYMPTOMS.csv
3)	*VAERSVAX.csv

These CSV files contain numbers, dates, and other unique values that can be mapped to their Vaccine Adverse Event Reporting System (VAERS) identification number for each person among the spreadsheets.  The VAERS was made by the Food and Drug Administration (FDA) and the Centers for Disease Control and Prevention (CDC) to collect data on adverse reactions that could be associated with vaccines in general.  

I pulled this data on 9/6/2024, which stated the data contains VAERS reports processed as of **08/30/2024**.

I filtered to only include those vaccines related to COVID19.  This dataset includes false positives for adverse reactions given a vaccine due to the encouragement towards doctors and other vaccine providers to report any adverse event if seen regardless of if they can prove the vaccine was the cause.  Therefore, the dataset contains a combination of coincidental events and those truly caused by the vaccine.  

The dataset I downloaded I have shared here on my GDRIVE for people to reproduce my work: 

https://drive.google.com/file/d/13ft2QazL4OugjftllcwjPXLUVMB8-2Xi/view?usp=drive_link
[data.csv](https://github.com/stevensmiley1989/BreastCancer/blob/master/Inputs/data.csv)



### 3 License <a class="anchor" id="6"></a>

This repository contains a variety of content; some developed by Steven Smiley, and some from third-parties.  The third-party content is distributed under the license provided by those parties.

The content developed by Steven Smiley is distributed under the following license:

*I am providing code and resources in this repository to you under an open source license.  Because this is my personal repository, the license you receive to my code and resources is from me and not my employer. 

   Copyright 2024 Steven Smiley

   Licensed under the Apache License, Version 2.0 (the "License");
   you may not use this file except in compliance with the License.
   You may obtain a copy of the License at

       http://www.apache.org/licenses/LICENSE-2.0

   Unless required by applicable law or agreed to in writing, software
   distributed under the License is distributed on an "AS IS" BASIS,
   WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
   See the License for the specific language governing permissions and
   limitations under the License.
   
