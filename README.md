# Stackoverflow_Survey_Analysis
 Analysis of Stackover flow surveys from 2011 to 2019

## Table of Contents
 <ol>
   <li><a href="#head1"> Libraries and tools used</a>
   <li><a href="#head2"> Motivation of the project </a>
   <li><a href="#head3"> Directory structure </a>
   <li><a href="#head4"> Summary of the results </a>
   <li><a href="#head5"> Acknowledgements </a>
   <li><a href="#head6"> Author </a>
</ol>

<h2 id="head1"> Libraries and tools used: </h2>
<ul>
 <li> Numpy
 <li> Pandas
 <li> MatPlotlib
 <li> Seaborn
 <li> Jupyter Notebook
</ul>

<h2 id="head2"> Motivation of the project</h2>

To apply skills learned as part of Udacity Data Science Nanodegree lesson to derive insights and identify relevant questions to answer.
In this project, I have used data collected from Stack Overflow survey conducted between 2011 and 2019.

<h2 id="head3"> Directory structure </h3>

```
.
├── Datasets                                               # Datasets used as the source of analysis 
    ├── 2011_Stack_Overflow_Survey_Results.csv
    ├── 2012_Stack_Overflow_Survey_Results.csv
    ├── 2013_Stack_Overflow_Survey_Responses.csv
    ├── 2014_Stack_Overflow_Survey_Responses.csv
    ├── 2015_Stack_Overflow_Developer_Survey_Responses.csv
    ├── 2016_Stack_Overflow_Survey_Responses.csv
    ├── 2017_survey_results_public.csv
    ├── 2018_survey_results_public.csv
    ├── 2019_survey_results_public.csv  
├── Stack_Overflow_Survey_Analysis.ipynb                    # Code compiled in Jupyter notebook
├── README.md                                               # ReadMe file

```

<h2 id="head4"> Summary of the results </h2>

I identified two questions common in surveys across the years - Language used and Job Satisfaction. After cleaning up the data, I dentified trends across the years.
**Top Languages**
![Trend - Top Languages](https://lh3.googleusercontent.com/EXWi4isOBVH6NLkIUlQCGdlDlSujV1E3a27ghsBPrHNY1lgKZDN7mX2CTlnblDPH8wGoiIzCGaLcksHpux21UQPVK8ItTM261ZNaf7HS2CdBYfCXa8NMAlxed-nmofZWC8rCeW-dcIc=w2400)
**Job Satisfaction**
![Trend - Job Satisfaction](https://lh3.googleusercontent.com/jq70NnTKEt2V6ZdNC_7LcwYWsRPLUArSDhlkppU_EQKj3n6IM_e4nSQNpQetLsyV8TRS6xCqBLvRh_ZzKGHcBcPIF2Ojy6au329yMju5NNYL6pZaHYg8eaFN3J6N-RBCVMJtQZj9baM=w2400)

After analysing all columns for 2019 survey results, I identified 4 questions to answer:
<ul>
 <li> Which Languages are gaining/losing Popularity
 <li> Which Database Environments are gaining/losing Popularity
 <li> Which Platforms are gaining/losing Popularity
 <li> Which Web Frameworks are gaining/losing Popularity
</ul>

**Languages**

![Language Comparision](https://lh3.googleusercontent.com/_AiBtSJ1hUj7oeXHDfGS4s54yrhhtQvdjF7O2eB_O333nVsmggv7XAPERKfDb6NfReRIFsDceh2igKVGWPURednOl-NTbm-4E7CTwaiEs0c3sjjoqQyE0ULbGTihZgsGPwfYYGVRpIo=w2400)

**Database Environments**

![Database Comparision](https://lh3.googleusercontent.com/Scc2E99PJz8JAW0Lhp6zdj8MLvxou7fW5t_u99SBIMoUCIdJ9xi_1FqKVKvyUqhZoqwV-_J4Fo2pRsvKIW5WEhOfQYJZtD-YY2Pqru-bjqNnj7NDuQQrOM7L73dqAHf1QPGDY_xaYNQ=w2400)

**Plaforms**

![Platform Comparision](https://lh3.googleusercontent.com/e-rGn3zAGOVQFvRA2oersNqXIVdVtgKRu23aFNjJbdCDOUzKOwN33qJI-NEg7bD-my3HxgBZztusK-DcD2xzSx7gg8w0cl296SBxByElEfrJ9bP7Ct6OZ4hZb5-3zYztAd2u7MdeejI=w2400)

**Web Frameworks**

![Framework Comparision](https://lh3.googleusercontent.com/b9rwNlNHneJi7ocFIXMbiZmpXHoHWylcTo_w6i39EgeCkAkJQmCrnYXRLUlvySFwqz5CEcFttuc3pmqBPnQJexEFBwXHR2N0e_IlnkHrqZdC7Ej7leaYGHY846rPtgkQU9IB9q5kpjg=w2400)

Link to Medium article based on the analysis - https://medium.com/@shahzeb.akhtar/an-analysis-of-top-programming-languages-and-technologies-7eb7683941a1

<h2 id="head5"> Acknowledgements </h2>

<ul>
 <li> Udacity https://www.udacity.com/
 <li> StackOverflow  https://insights.stackoverflow.com/survey
</ul>

<h2 id="head6"> Author </h2>

Shahzeb Akhtar

https://www.linkedin.com/in/shahzebakhtar/
