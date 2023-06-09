# Saudi Privacy Policy Dataset
The Saudi Privacy Policy Dataset is a comprehensive collection of privacy policies from various sectors in Saudi Arabia, annotated according to the 10 principles of the Personal Data Protection Law (PDPL). The dataset includes 1,000 websites, 4,638 lines of text, 775,370 tokens, and a corpus size of 8,353 KB. This dataset is valuable for researchers, policymakers, and industry professionals interested in understanding and promoting compliance with privacy regulations in Saudi Arabia.
# Data Collection
Data were acquired from various sources, including the Saudi Central Bank, Saudi Arabia National United Platform, and the Council of Health Insurance. General websites were found using Google and Wikipedia, with classification-based searching on Wikipedia for easier discovery of Saudi-owned websites. Due to irrelevant information and other challenges, data were manually scraped, extracting only required information. Only the first web page of privacy policies was collected, discarding PDF files, additional links, and websites with disabled copy-text functionality.
# Data Preprocessing
Text was manually cleaned while scraping, removing introductions, contact details, and hyperlinks. Privacy policies were combined into a CSV file, followed by data normalization. Using Python regular expressions, Arabic diacritics, English letters, symbols, and numbers were removed. Blank lines, rows, and multi spaces in cells were also eliminated.
# Usage
You can use this dataset for various applications, such as assessing privacy policy compliance, benchmarking privacy practices across industries, and developing automated tools for monitoring adherence to data protection regulations. By providing a comprehensive and annotated dataset of privacy policies, the Saudi Privacy Policy Dataset aims to facilitate further research and development in the areas of privacy policy analysis, natural language processing, and machine learning applications related to privacy and data protection.
# License
This dataset is released under the [MIT License](https://opensource.org/license/mit/).
## Citation
``` 
@article{Al-Khalifa2023,
  title={The Saudi Privacy Policy Dataset},
  author={Hend Al-Khalifa, Malak Mashaabi, Ghadi Al-Yahya, and Raghad Alnashwan},
  journal={arXiv preprint [arXiv:2304.00257](https://arxiv.org/abs/2304.02757)},
  year={2023}
}
```
