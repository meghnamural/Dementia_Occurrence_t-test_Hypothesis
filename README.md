# Demetia-Occurrence
Estimation of dementia occurrence from MRI Data using test hypothesis

Alzheimer's disease is a progressive disease that destroys memory and other important mental functions. Memory loss and confusion are the main symptoms of this condition. 

I have considered a diverse dataset consisting  60 subjects diagnosed with various levels of dementia (normal to moderate levels ) belonging to different age groups

Factors considered in this Test

* Clinical Dementia Rating(CDR)

* Mini Mental Status Examination (MMSE)

* Estimated Total Intracranial Volume(eTIV)

* Normalize Whole Brain Volume(nWBV)

### Clinical Dementia Rating

The Clinical Dementia Rating (CDR) is a widely utilized clinical tool for grading the relative severity of dementia with scores that range from 0 (no impairment) to 3 (severe impairment).

We base our hypothesis on the normal levels of CDR and determine the affinity of two samples to dementia. The population means are given in the table below,

![](/Users/Meghna/Desktop/table.png)

The above table gives a clear listing of the normal rates of CDR, MMSE, eTIV and nWBV.


Below is the Age vs CDR composition in our dataset

![](/Users/Meghna/Desktop/image1.png)

## Test Hypothesis

We will now consider two diverse samples comprising of both men and women and determine the average levels of dementia of the two groups based on the MMSE,eTIV and nWBV levels.

One way to test this is by conducting a Student's t-test on the basis of the normal levels of in the three categories.

#### I have uploaded my codes and outputs as an R Markdown file.

## Hypothesis Results for the two samples

* Mini Mental Status Examination (MMSE)

![](/Users/Meghna/Desktop/MMSE.png)

* Estimated Total Intracranial Volume(eTIV)

![](/Users/Meghna/Desktop/eTIV.png)

* Normalize Whole Brain Volume(nWBV)

![](/Users/Meghna/Desktop/nWBV.png)
