## Building an Auto-Tagging system for  Q&A from Cross Validated, the Stack Exchange statistics site
### About Dataset 
Full text of questions and answers from Cross Validated, the statistics and machine learning Q&A site from the Stack Exchange network.

**This is organized as three tables:**

- Questions contains the title, body, creation date, score, and owner ID for each question.
- Answers contains the body, creation date, score, and owner ID for each of the answers to these questions. The ParentId column links back to the Questions table.
- Tags contains the tags on each question
For space reasons only non-deleted and non-closed content are included in the dataset. The dataset contains questions up to 19 October 2016 (UTC).
- Dataset:
  https://www.kaggle.com/datasets/stackoverflow/statsquestions#Questions.csv
### LicenseI
All Stack Exchange user contributions are licensed under CC-BY-SA 3.0 with attribution required
