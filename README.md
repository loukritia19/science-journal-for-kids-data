# Science Journal for Kids Data

This repository contains a dataset of abstracts from the Science Journal for Kids website and the original academic papers. It includes metadata such as titles, URLs, reading levels, and links to the full academic papers. The dataset is designed to support research and analysis of educational content tailored for young learners.

## Data

The dataset is a curated collection of 284 original scientific abstracts and their adapted abstracts for children. These summaries are sourced from the [Science Journal for Kids (SJK)](https://www.sciencejournalforkids.org/), a platform dedicated to making scientific research accessible and engaging for younger audiences. The dataset covers a diverse range of subjects, including biology, chemistry, health, environmental science, and more. The CSV file is approximately 716 KB in size.

## Data Format

The dataset includes the following columns:

- **Category**: The category or categories to which the article belongs. This can include areas such as Biodiversity, Conservation, Biology, Chemistry, Health, and Environmental Science.
- **Title**: The title of the article, providing a concise description of the main topic or finding of the research.
- **Kids Abstract**: The abstract of the article aimed at a younger audience.
- **Abstract (Original academic paper)**: The abstract from the original academic paper.
- **URL (Original academic paper)**: The URL to access the original academic paper.
- **Reading Levels**: The suggested reading levels for the lay summary, which may include Elementary school, Middle school, Lower high school, and Upper high school. 

## Citing this Repository

If you use this dataset in your research, please cite it using the following BibTeX entry:

```bibtex
@inproceedings{BioLaySumm_2024,
  author       = {Loukritia Stefanou and Tatiana Passali and Grigorios Tsoumakas},
  title        = {AUTH at BioLaySumm 2024: Bringing Scientific Content to Kids},
  booktitle    = {Proceedings of the ACL 2024 BioNLP Workshop},
  year         = {2024},
  address      = {Bangkok, Thailand},
  note         = {A paper presented at the BioLaySumm 2024 shared task on lay summarization of biomedical research articles.}
}

