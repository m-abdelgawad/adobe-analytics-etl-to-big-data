<a name="readme-top"></a>

[![LinkedIn][linkedin-shield]][linkedin-url]



<!-- PROJECT LOGO -->
<br />
<div align="center">
  <img src="readme_files/logo.png" alt="Logo" width="80" height="80">
  <h3 align="center">Adobe Analytics ETL to Big Data</h3>
</div>



<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#business-case">Business Case</a></li>
        <li><a href="#technical-solution">Technical Solution</a></li>
        <li><a href="#production-environment">Production Environment</a></li>
        <li><a href="#tech-stack">Tech Stack</a></li>
      </ul>
    </li>
    <li><a href="#contact">Contact</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project

* Project Name: Adobe Analytics ETL to Big Data
* Version: v1.0.0
* Organization Department: Technology


### Business Case
This project encompasses two distinct business cases that leverage advanced data management techniques to enhance business insights and customer engagement.

In the first scenario, during Ramadan 2023, an Extract, Transform, Load (ETL) process was executed to acquire and consolidate Fawazeer data from the Ana Vodafone platform. These data sets were subsequently transferred and stored on dedicated Big Data servers, setting the stage for subsequent modeling within the Data Warehouse framework. This endeavor aims to derive valuable insights from the Fawazeer interactions during Ramadan, enabling the organization to make informed decisions based on user behavior and preferences.

Concurrently, the second use case involves the extraction of pertinent data concerning the "Happy Hour" summer promotion of 2023. This initiative revolves around assessing network speeds experienced by users during the promotional period and rewarding them with gifts in alignment with their network experiences. Following extraction, the amassed data is loaded onto the Big Data servers, ready for transformation and eventual integration into the Data Warehouse. By adopting this approach, the organization can distill actionable insights from user interactions during the "Happy Hour" campaign, paving the way for strategic improvements and more personalized customer interactions.

<p align="right">(<a href="#readme-top">back to top</a>)</p>


### Technical Solution
The technical solution entails an ETL (Extract, Transform, Load) process that is intricately designed to extract, decrypt, transform, and load data from Adobe Analytics servers onto dedicated Big Data servers. The workflow is orchestrated to enhance data quality and accessibility, and it is scheduled to run daily at 2 AM using the crontab utility.

The ETL process begins by establishing a connection through a proxy to access the Adobe Analytics servers. The proxy safeguards the connection and facilitates secure data retrieval, maintaining the confidentiality and integrity of the encrypted data. This access enables the extraction of encrypted data sets from Adobe Analytics.

Upon extraction, the encrypted data undergoes a decryption phase. This decryption process involves the application of appropriate cryptographic algorithms and keys to unveil the original data in its raw form. The decrypted data subsequently undergoes meticulous validation to identify and address any data format anomalies or inconsistencies.

During the transformation phase, data format issues are rectified to ensure uniformity and coherence within the dataset. This may involve tasks such as reformatting date and time fields, correcting data types, and harmonizing naming conventions. The transformed data is then prepared for loading onto the Big Data servers.

The loading phase involves transferring the transformed data to dedicated Big Data servers. These servers are optimized to handle large volumes of data efficiently, ensuring seamless storage and accessibility for subsequent analysis. The loading process is designed to be robust, allowing for data integrity checks and error handling to guarantee the accuracy of the loaded data.

To maintain a regular and consistent data flow, the entire process is automated and scheduled using the crontab utility. The ETL workflow is orchestrated to execute daily at 2 AM, ensuring that the latest data is captured and processed in a timely manner. This automation minimizes manual intervention and enhances data currency for analytical purposes.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

### Production Environment
**Hosting:** 

**Confidential**


**Project Directory:**

**Confidential**


**Service Accounts:** 
* None



<p align="right">(<a href="#readme-top">back to top</a>)</p>


### Tech Stack

This project was developed using the following tech stack:

* Bash (Shell) Scripting

<p align="right">(<a href="#readme-top">back to top</a>)</p>


<!-- CONTACT -->
## Contact

Mohamed AbdelGawad Ibrahim - [@m-abdelgawad](https://www.linkedin.com/in/m-abdelgawad/) - <a href="tel:+201069052620">+201069052620</a>

<p align="right">(<a href="#readme-top">back to top</a>)</p>


<!-- MARKDOWN LINKS & IMAGES -->
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://www.linkedin.com/in/m-abdelgawad/
