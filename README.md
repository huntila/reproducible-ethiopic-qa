# Ensuring Reproduciblity in Ethiopic Language Question Answering

## Question Answering (QA)
Question Answering (QA) systems answer natural language questions using specific underlying data sources. Ethiopic QA, in particular, is dedicated to responding to questions posed in Ethiopic languages, such as Amharic, Tigrinya, Afan Oromo, Somali, and others.
As shown in the figure below, it is a de facto to use datasets for training, evaluating, and comparing QA models.
![qa_dataset_importance](https://github.com/user-attachments/assets/7c340b37-b247-49c7-9177-6f750fc1c972)

In Ethiopic QA, despite the existence of QA models for languages such as Amharic, Tigrinya, and Afan Oromo, only a few publicly available datasets exist (See Dataset table). Furthermore, these datasets often lack detailed information in their accompanying dataset cards and do not always provide corresponding baseline models.

| Dataset                              | Language | Publicly Available Repo | Hugging Face (HF) Data Card | Method of Creation                  | Baseline Model | Baseline Code |
|--------------------------------------|----------|-------------------------|-----------------------------|-------------------------------------|----------------|---------------|
| Amh-QuAD [Taffa et al., 2024](https://aclanthology.org/2024.rail-1.14.pdf)       | Amharic  | GitHub & HF             | Yes                         | Crowd-sourcing                      | Yes            | GitHub        |
| AmaSQuAD [Hailemariam et al., 2025](https://arxiv.org/pdf/2502.02047)         | Amharic  | HF                      | Yes                         | Translation                         | No             | -             |
| Question Classification [Destaw et al., 2022](https://aclanthology.org/2022.sigul-1.18.pdf) | Amharic  | HF                      | No                          | Collected from Community-based QA platform | Yes            | GitHub        |
| TigQA [Teklehaymanot et al., 2024](https://aclanthology.org/2024.lrec-main.1404.pdf)   | Tigrinya | GitHub & Zenodo         | No                          | Expert curated                      | Yes            | GitHub        |
| TiQuAD [Gaim et al., 2023](https://aclanthology.org/2023.acl-long.661.pdf)          | Tigrinya | No                      | No                          | Crowd-Sourcing & Translation        | Yes            | -             |


## Why Reproducibiltiy?
Reproducibility - enables others to verify and build upon someone work. In the context of low-resource Question Answering (QA), it becomes even more crucial due to the challenges posed by limited data availability. This GitHub page aims to share best practices to enhance reproducibility in low-resource QA research, specifically Ethiopic languages QA. Generally, reproducibility promots:
- Verification of Results: allows others to verify findings by replicating experiments or analyses.
- Building on Previous Work: When research is reproducible, others can build upon it, advancing the field more effectively. It enables researchers to use previous studies as a foundation for further innovation and exploration. 
- Transparency and Trust: enhances the transparency of research processes, fostering trust within the scientific community and among the public. It demonstrates rigorous methodology and reduces the likelihood of errors or fraudulent practices. 
- Identification of Errors: help identifying mistakes or biases in research, whether they arise from methodological flaws, data mishandling, or other issues. 
- Efficiency and Resource Sharing: Researchers can save time and resources by accessing reproducible studies, avoiding redundant efforts in recreating methods or data processing steps. 
- Improved Collaboration: Reproducibility promotes collaboration by providing clear guidelines and detailed documentation that others can follow. 

## Strategies for Enhancing Reproducibility in Low-Resource QA Systems

| Category                     | Details                                                                                      |
|----------------------------------|-------------------------------------------------------------------------------------------------|
| Language-Specific Considerations | Community Engagement: Collaborate with native speakers and local researchers to validate datasets and methodologies. |
| Transparent Reporting            | - Follow standardized guidelines, such as the ML Reproducibility Checklist, to enhance transparency. <br> - Provide both qualitative and quantitative error analyses of model performance. <br> - Conduct ablation studies to assess the impact of various components in the QA pipeline. |
| Community-Driven Initiatives     | - Organize shared tasks dedicated to Ethiopic QA to foster collaboration and benchmarking. <br> - Create awareness about reproducibility challenges. <br> - Support localized research efforts: Invest in research initiatives that focus on building and sustaining systems for underrepresented languages. |

## Resource
- [Model Card Guidebook](https://huggingface.co/docs/hub/en/model-card-guidebook)
- [Dataset Cards](https://huggingface.co/docs/hub/en/datasets-cards)

## Hands on Exercise
[Automated model card creation](https://huggingface.co/spaces/huggingface/Model_Cards_Writing_Tool)
[Dataset card creation](https://huggingface.co/new-dataset)

### Acknowledgements
For this GitHub page we have used: 
-  Ozoani, Ezi and Gerchick, Marissa and Mitchell, Margaret. Model Card Guidebook. [Hugging Face, 2022.](https://huggingface.co/docs/hub/en/model-card-guidebook)
-  [Model and Data Documentation for AI](https://github.com/krangelie/model-and-data-cards-rdm4ai2024?tab=readme-ov-file)
