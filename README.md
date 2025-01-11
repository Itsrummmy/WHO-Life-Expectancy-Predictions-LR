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

Project involved building two linear regression models to predict life expectancy using a dataset from 2000 and 2015. The first model is designed to prioritize precision, while the second is simplified to focus on ethical considerations. 

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



<!-- Deliverables -->
## Deliverables

Notebook with different sections of the model (EDA, feature engineering, modelling, testing) including a separate notebook containing the interactive function.




<!-- Outcomes -->
## Outcomes

* The test Root Mean Square Error for both models (robust and ethical) were 0.557 and 1.619 (7 months and 1 year, 9 months) respectively.
* The ethical model exhibits a high degree of feature sparsity, relying solely on adult mortality and infant deaths as predictive variables.
* The ethical model emerged as our preferred choice for predicting life expectancy due to its demonstrable lack of bias, and aligning with all our ethical considerations.



<!-- Conclusion -->
## Conclusion

This project effectively delivered two predictive linear regression models and an interactive function for estimating life expectancy, prioritizing both model precision and ethical standards. The robust model demonstrated superior predictive performance with a much lower RMSE, while the ethical model provided a more globally acceptable alternative with no significant biases.


<p align="left">(<a href="#readme-top">back to top</a>)</p>

