I have two consulting businesses: Singular Value Consulting and Kingwood Data Privacy. Singular Value Consulting focuses on applied mathematics: mathematical modeling, dignal processing, statistical analysis, etc. Kingwood Data Privacy focuses, not surprisingly, on data privacy and related regulations such as [HIPAA](https://www.johndcook.com/blog/expert-hipaa-deidentification/) and [CCPA](https://www.johndcook.com/blog/ccpa/).

Kingwood Data Privacy is newer. At first we were doing data privacy work under the Singular Value Consulting umbrella, but then We decided to split off data privacy into a separate company.

# Privacy for Individuals and Companies

Data privacy typically means protecting the privacy of individuals represented in a data set such as insurance claim data, electronic medical records, or pharmacy prescription data. However, sometime it means protecting the privacy of a company. Companies are not natural persons and not protected by HIPAA or other privacy laws, but nevertheless there are times when a corporation would like to contribute data to a project while protecting its intellectual property. 

# Differential privacy

[Differential privacy](https://www.johndcook.com/blog/differential-privacy/) is a useful tool for protecting individual privacy as well as corporate intellectual property. The focus is usually on the former: protecting individual privacy. Differential privacy insures, in a way that can be made mathematically precise, that it makes little difference whether an individual participates in a database or not. Database query results have a calibrated amount of randomness added, enough to protect privacy but ideally not enough to significantly diminish the usefulness of the result. For example, if you want to report the average age in a database of thousands of people, a tiny amount of randomness is enough to obscure any particular person's participation in the database. But the more risk a query poses to an individual, the more noise is added to the result.

Companies can share data using differential privacy while retaining their individual data. The companies are not releasing their data per se; they are releasing the ability to query the data via differentially private mechanisms. 
