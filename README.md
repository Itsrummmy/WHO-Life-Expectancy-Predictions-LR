<a id="readme-top"></a>

# WHO Life Expectancy Predictions Project

<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#project-overview">Project Overview</a>
    </li>
    <li>
      <a href="#tools-used">Tools Used</a>
    </li>
    <li>
      <a href="#deliverables">Deliverables</a>
    </li>
    <li>
      <a href="#outcomes">Outcomes</a>
    </li>
    <li>
      <a href="#conclusion">Conclusion</a>
  </ol>
</details>



<!-- PROJECT OVERVIEW -->
## Project Overview

Project involved building two linear regression models to predict life expectancy using a dataset from 2000 and 2015. The first model is designed to prioritize accuracy, while the second is simplified to focus on ethical considerations. 

<p align="right">(<a href="#readme-top">back to top</a>)</p>


<!-- Tools Used -->
## Tools Used

* **Python**: For exploratory data analysis and modeling.
* **Libraries**:
  * `numpy`
  * `pandas`
  * `matplotlib`
  * `seaborn`
  * `sklearn`
  * `statsmodels`

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- Deliverables -->
## Deliverables

* Code broken down in relevant sections across multiple .ipynb files (EDA, feature engineering, modelling, testing).
* An interactive function, which must work by itself in an individual .ipynb file.

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- Outcomes -->
## Outcomes

* The R-Squrared statistic for the accurate and ethical model was 0.984 and 0.944 respectively.
* The RMSE on the test data for both models was 1.243 and 2.213 respectively (outperforming the given baseline).
* The Country feature was found to be far too powerful in predicting life expectancy so any prediction would be dependent on the country rather than any other inputted features. This raised ethical concerns for underperforming countries so this feature was removed from both models.
* Features relating to immunisation converage and disease incidence were removed from the ethical model because these features reflect directly on the healthcare infrastructure of the country which could put financial pressure on a country to increases funding.
* Features relating to thinness prevalence are a reflection on levels of nutrition across a country which is sensitive information. These features were therefore removed from the ethical model.


<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- Conclusion -->
## Conclusion

This project effectively delivered two predictive linear regression models and an interactive function for estimating life expectancy, prioritizing both accuracy and ethical standards. The accuracte model demonstrated superior predictive performance with a lower RMSE, while the ethical model provided a privacy-focused alternative. These results highlight the capability of data-driven approaches to deliver impactful, ethical, and scalable solutions in the realm of public health.


<p align="right">(<a href="#readme-top">back to top</a>)</p>
