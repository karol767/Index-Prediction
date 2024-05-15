# CIS 5190 Final Project

## Project Name

Gendered Pathways in Science:Exploring the Impact of Researcher Gender on Academic Success

## Team Member

- Zed Liu
- Deniel Shumeiko

## Important Files

- [Raw Data](Data)
- [Code](Code.ipynb)
- [Presentation Video](Presentation.mp4)
- [Presentation Silde](Slide.pptx)

## Project Overview

In this project, we investigate the impact of researcher gender on academic success, using the H-index as our primary target metric. This study is crucial as it provides insights into the factors influencing a researcher’s academic impact and examines potential gender bias in academic settings.

Our primary goal was to compile an extensive dataset of researchers’ backgrounds, affiliations, and publications in the Human-Computer Interaction (HCI) domain. We then aimed to predict academic impact quantified by the H-index by using Machine Learning (ML) algorithms such as Linear Regression, AdaBoost Regression, Random Forest, and Feed Forward Neural Networks (FFNN).

We created a dataset with 3,453 rows and 17 columns, covering features like H-index, total citations, university ranking, and gender. Our models showed strong predictive power for the H-index. By toggling the gender feature in the testing set, we found no major gender bias in HCI research. Our investigation also found that out of all ML methods, custom-made FFNN showed the highest accuracy on the test dataset, making it the model of choice for the proposed problem.