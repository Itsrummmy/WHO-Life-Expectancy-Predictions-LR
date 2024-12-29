<a id="readme-top"></a>

# WHO Life Expectancy Predictions Project

## Project 4 of the Digital Futures Academy

<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
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
    </li>
    <li><a href="#contact">Contact</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project

This project is the final assignment for the continuous modelling section of the Predictive Modelling module at Digital Futures Academy. I developed two linear regression models to predict life expectancy for each country in the dataset between 2000 and 2015. The first model is designed to prioritize accuracy, while the second is simplified to focus on ethical considerations, particularly regarding the inclusion of features that may have financial implications for countries. Throughout the project, I balanced model complexity with accuracy, considering whether slight improvements in RMSE justify the inclusion of insignificant features that may add unnecessary complexity. The goal was to create trustworthy, ethically sound models that are sensitive to the data privacy concerns of individual countries. The baseline RMSE for the accurate model was set at 2 for this project.

<p align="right">(<a href="#readme-top">back to top</a>)</p>


<!-- Tools Used -->
## Tools Used

* **Python**: For exploratory data analysis and modeling.
* **Jupyter Lab**: IDE for the project.
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



<!-- CONTACT -->
## Contact

Katrina Booth: katrinalilybooth@gmail.com

Project Link: [https://github.com/KatrinaBooth/WHO-Life-Expectancy-Predictions](https://github.com/KatrinaBooth/WHO-Life-Expectancy-Predictions)

<p align="right">(<a href="#readme-top">back to top</a>)</p>
