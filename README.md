++<!-- Improved compatibility of back to top link: See: https://github.com/othneildrew/Best-README-Template/pull/73 -->
<a id="readme-top"></a>
<!--
*** Thanks for checking out the Best-README-Template. If you have a suggestion
*** that would make this better, please fork the repo and create a pull request
*** or simply open an issue with the tag "enhancement".
*** Don't forget to give the project a star!
*** Thanks again! Now go create something AMAZING! :D
-->



<!-- PROJECT SHIELDS -->
<!--
*** I'm using markdown "reference style" links for readability.
*** Reference links are enclosed in brackets [ ] instead of parentheses ( ).
*** See the bottom of this document for the declaration of the reference variables
*** for contributors-url, forks-url, etc. This is an optional, concise syntax you may use.
*** https://www.markdownguide.org/basic-syntax/#reference-style-links
-->
[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![MIT License][license-shield]][license-url]
[![LinkedIn][linkedin-shield]][linkedin-url]



<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="https://github.com/OtnielGomes/0_Portfolio-Credit_Risk_Analysis_with_Pytorch">
    <img src="images/logo.jpg" alt="Logo" width="200" height="100">
  </a>

<h3 align="center"> Credit Risk Analysis - Lending Club </h3>

  <p align="center">
    Classification of requested loans using Pytorch as the main classification model
    <br />
    <a href="https://github.com/OtnielGomes/0_Portfolio-Credit_Risk_Analysis_with_Pytorch"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    <a href="https://github.com/OtnielGomes/0_Portfolio-Credit_Risk_Analysis_with_Pytorch">View Demo</a>
    ·
    <a href="https://github.com/OtnielGomes/0_Portfolio-Credit_Risk_Analysis_with_Pytorch/issues/new?labels=bug&template=bug-report---.md">Report Bug</a>
    ·
    <a href="https://github.com/OtnielGomes/0_Portfolio-Credit_Risk_Analysis_with_Pytorch/issues/new?labels=enhancement&template=feature-request---.md">Request Feature</a>
  </p>
</div>



<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#roadmap">Roadmap</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#acknowledgments">Acknowledgments</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project

<br />
<div align="center">
  <a href="https://github.com/OtnielGomes/0_Portfolio-Credit_Risk_Analysis_with_Pytorch">
    <img src="images/logoLC.jpeg" alt="Logo Lendin Club" width="700" height="350">
  </a>
</div>

# Description:

* This project will be built and implemented using the **Azure Databricks** environment, where classifiers will be built with neural network/machine learning models that will seek to predict whether a loan will be paid or not. The basis of the project will be a PyTorch model that will classify the requested loans. In the final model, a classifier will be created that will use the selected model together with some variables and information from the loan applicant to make the final classification, where the loans will be classified into 4 stages of default risk. According to the defined parameters, the classifier will decide whether the loan should be approved or rejected immediately, or if there is the possibility of a reassessment by the institution's stakeholders.

* In this project, I will work with a dataset taken from Kaggle, where I will perform a credit risk analysis. The data provided comes from LendingClub, a financial services company based in San Francisco, California. LendingClub was the first peer-to-peer lending platform to register its offerings as securities with the Securities and Exchange Commission (SEC) and to offer loan trading on a secondary market. The company offers personal loans of up to $40,000, with terms ranging from 24 to 60 months, and operates entirely online, with no physical branches.

* In this project, I will apply the CRISP-DM method, which follows the following steps:

  * 1-**Business understanding**:
  
    What does the business need?
  
  * 2-**Data understanding**:
  
    What data do we have/need? Is it clean?
  
  * 3-**Data preparation**:
  
    How do we organize the data for modeling?
  
  * 4-**Modeling**:
  
    What modeling techniques should we apply?
  
  * 5-**Evaluation**:
  
    What best meets the business objectives?
  
  * 6-**Implementation**:
  
    How do stakeholders access the results?

<p align="right">(<a href="#readme-top">back to top</a>)</p>



### Built With
* [![Databricks][Azure Databricks]][Azure Databricks-url]
* [![Language Python][Python]][Python-url]
* [![Apache][Apache Spark]][Apache Spark-url]
* [![PD][Pandas]][Pandas-url]
* [![NP][NumPy]][NumPy-url]
* [![Matplot][Matplotlib]][Matplotlib-url]
* [![Ploty Lib][Plotly]][Plotly-url]
* [![Torch][PyTorch]][PyTorch-url]
* [![Sklearn][scikit-learn]][scikit-learn-url]
* [![Ray][Ray Tune]][Ray Tune-url]

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- GETTING STARTED -->
## Getting Started

### Prerequisites

* Data Bricks - This project was developed in the Databricks environment, so the entire project structure is compatible with AzureDatabricks and Databricks Community. Below I will leave the link to create an account in the Databricks Community where it is free and at no cost and you will be able to run a copy of this project perfectly.
Link for create acount :

* [![Databricks CM][Azure Databricks CM]][Azure Databricks CM-url]

##### Now that your account is created, you will need to create a cluster in DataBricks. Below is the step-by-step guide to creating the cluster.

###### Step-by-Step Guide to Creating a Cluster in Databricks

* 1 **Access Databricks**:
  - Log in to your Databricks account.

* 2 **Navigate to the Clusters Section**:
  - In the side menu, click on **Compute** (or **Clusters**).

* 3 **Create a New Cluster**:
  - Click on the **Create Cluster** button.

* 4 **Configure the Cluster**:
  - **Cluster Name**: Give your cluster a name.
  - **Cluster Mode**: Choose the cluster mode (Standard, High Concurrency, etc.).
  - **Databricks Runtime Version**: Select the version of Databricks Runtime you want to use.
  - **Node Type**: Choose the node type (virtual machine) for the workers and the driver. - **Autoscaling**: Enable or disable autoscaling. If enabled, set the minimum and       maximum number of nodes.
  - **Worker Nodes**: Set the number of worker nodes.
  - **Driver Node**: Configure the driver node if necessary.
  - **Version used in this project**: 15.4 LTS (includes Apache Spark 3.5.0, Scala 2.12)

* 5 **Advanced Settings (Optional)**:
  - **Libraries**: Add libraries that the cluster should load when starting.
  - **Spark Configurations**: Add Spark-specific configurations.
  - **Environment Variables**: Set environment variables if necessary.

* 6 **Create the Cluster**:
  - After configuring all options, click **Create Cluster**.

* ###### Additional Resources

* **Official Documentation**: See the official Databricks documentation for more details and advanced options: [Click here](https://learn.microsoft.com/en-us/azure/databricks/scenarios/quickstart-create-databricks-workspace-vnet-injection).


### Installation of librarys

1. Install Libraries to the Cluster:

  * After creating the cluster, click on the cluster name to open its settings.

  *  Go to the Libraries tab.

  * Click Install New.

  * Choose the library source (e.g., PyPI, Maven, CRAN, DBFS, etc.).

  * Follow the instructions to install the desired library. For example, to install a library from PyPI, enter the package name and click Install.

2. threadpoolctl: **PyPI**
   ```sh
   threadpoolctl==3.5.0
   ```
3. spark-excel_2.12:0.14.0: **Marven**
   ```sh
   com.crealytics:spark-excel_2.12:0.14.0
   ```
4. scikit-learn: **PyPI**
   ```sh
   scikit-learn==1.5.2
   ```
5. category_encoders: **PyPI**
   ```sh
   category_encoders==2.6.3
   ```
6. torch: **PyPI**
   ```sh
   torch==2.5.1
   ```
7. torchmetrics: **PyPI**
   ```sh
   torchmetrics==1.4.2
   ```
8. xgboost: **PyPI**
   ```sh
   xgboost==2.1.0
   ```
8. ray[tune]: **PyPI**
   ```sh
   ray[tune]==2.38.0
   ```

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- USAGE EXAMPLES -->
## The Project

Use this space to show useful examples of how a project can be used. Additional screenshots, code examples and demos work well in this space. You may also link to more resources.

_For more examples, please refer to the [Documentation](https://example.com)_

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- ROADMAP -->
## Roadmap

- [ ] Feature 1
- [ ] Feature 2
- [ ] Feature 3
    - [ ] Nested Feature

See the [open issues](https://github.com/OtnielGomes/0_Portfolio-Credit_Risk_Analysis_with_Pytorch/issues) for a full list of proposed features (and known issues).

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- CONTRIBUTING -->
## Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement".
Don't forget to give the project a star! Thanks again!

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

<p align="right">(<a href="#readme-top">back to top</a>)</p>

### Top contributors:

<a href="https://github.com/github_username/repo_name/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=github_username/repo_name" alt="contrib.rocks image" />
</a>



<!-- LICENSE -->
## License

Distributed under the MIT License. See `LICENSE.txt` for more information.

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- CONTACT -->
## Contact

Your Name - [@twitter_handle](https://twitter.com/twitter_handle) - email@email_client.com

Project Link: [https://github.com/github_username/repo_name](https://github.com/github_username/repo_name)

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- ACKNOWLEDGMENTS -->
## Acknowledgments

* []()
* []()
* []()

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/OtnielGomes/0_Portfolio-Credit_Risk_Analysis_with_Pytorch.svg?style=for-the-badge
[contributors-url]: https://github.com/OtnielGomes/0_Portfolio-Credit_Risk_Analysis_with_Pytorch/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/OtnielGomes/0_Portfolio-Credit_Risk_Analysis_with_Pytorch.svg?style=for-the-badge
[forks-url]: https://github.com/OtnielGomes/0_Portfolio-Credit_Risk_Analysis_with_Pytorch/network/members
[stars-shield]: https://img.shields.io/github/stars/OtnielGomes/0_Portfolio-Credit_Risk_Analysis_with_Pytorch.svg?style=for-the-badge
[stars-url]: https://github.com/OtnielGomes/0_Portfolio-Credit_Risk_Analysis_with_Pytorch/stargazers
[issues-shield]: https://img.shields.io/github/issues/OtnielGomes/0_Portfolio-Credit_Risk_Analysis_with_Pytorch.svg?style=for-the-badge
[issues-url]: https://github.com/OtnielGomes/0_Portfolio-Credit_Risk_Analysis_with_Pytorch/issues
[license-shield]: https://img.shields.io/github/license/OtnielGomes/0_Portfolio-Credit_Risk_Analysis_with_Pytorch.svg?style=for-the-badge
[license-url]: https://github.com/OtnielGomes/0_Portfolio-Credit_Risk_Analysis_with_Pytorch/blob/master/LICENSE.txt
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/in/otnielgomes
[product-screenshot]: images/screenshot.png
[Next.js]: https://img.shields.io/badge/next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white
[Next-url]: https://nextjs.org/
[React.js]: https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB
[React-url]: https://reactjs.org/
[Vue.js]: https://img.shields.io/badge/Vue.js-35495E?style=for-the-badge&logo=vuedotjs&logoColor=4FC08D
[Vue-url]: https://vuejs.org/
[Angular.io]: https://img.shields.io/badge/Angular-DD0031?style=for-the-badge&logo=angular&logoColor=white
[Angular-url]: https://angular.io/
[Svelte.dev]: https://img.shields.io/badge/Svelte-4A4A55?style=for-the-badge&logo=svelte&logoColor=FF3E00
[Svelte-url]: https://svelte.dev/
[Laravel.com]: https://img.shields.io/badge/Laravel-FF2D20?style=for-the-badge&logo=laravel&logoColor=white
[Laravel-url]: https://laravel.com
[Bootstrap.com]: https://img.shields.io/badge/Bootstrap-563D7C?style=for-the-badge&logo=bootstrap&logoColor=white
[Bootstrap-url]: https://getbootstrap.com
[JQuery.com]: https://img.shields.io/badge/jQuery-0769AD?style=for-the-badge&logo=jquery&logoColor=white
[JQuery-url]: https://jquery.com 

[Azure Databricks]: https://img.shields.io/badge/Databricks-FF3621?style=for-the-badge&logo=Databricks&logoColor=white
[Azure Databricks-url]:  https://azure.microsoft.com/en-us/pricing/purchase-options/azure-account?icid=databricks

[PyTorch]: https://img.shields.io/badge/PyTorch-%23EE4C2C.svg?style=for-the-badge&logo=PyTorch&logoColor=white
[PyTorch-url]: https://pytorch.org

[scikit-learn]: https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white
[scikit-learn-url]: https://scikit-learn.org/stable/

[Apache Spark]: https://img.shields.io/badge/Apache%20Spark-FDEE21?style=flat-square&logo=apachespark&logoColor=black
[Apache Spark-url]: https://spark.apache.org/

[Pandas]: https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white
[Pandas-url]: https://pandas.pydata.org/

[Ray Tune]: https://img.shields.io/badge/Ray-028CF0.svg?style=for-the-badge&logo=Ray&logoColor=white
[Ray Tune-url]: https://docs.ray.io/en/latest/tune/index.html

[Matplotlib]: https://img.shields.io/badge/Matplotlib-%23ffffff.svg?style=for-the-badge&logo=Matplotlib&logoColor=black
[Matplotlib-url]: https://matplotlib.org/

[Plotly]: https://img.shields.io/badge/Plotly-%233F4F75.svg?style=for-the-badge&logo=plotly&logoColor=white
[Plotly-url]: https://plotly.com/graphing-libraries/

[NumPy]: https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white
[NumPy-url]: https://numpy.org/

[Python]: https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54
[Python-url]: https://www.python.org/

[Azure Databricks CM]: https://img.shields.io/badge/Databricks-FF3621?style=for-the-badge&logo=Databricks&logoColor=white
[Azure Databricks CM-url]: https://community.cloud.databricks.com/
