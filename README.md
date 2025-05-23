**AI & Machine Learning (KAN-CINTO4003U) - Copenhagen Business School | Spring 2025**

***

### Group members
| Student name | Student ID |
| --- | --- |
| Claudio Thumm | 173663 |
| Nikolaos Tsatsampas | 172760 |
| Petyo Zhechev | 157382 |

<br>


## 📂 Project Structure
```
├── 📁 data/
│    ├── 📄 jobposts.csv # Raw job post data
│    ├── 📄 resume.csv # Raw resume data
│    └── 📁 processed/
│         ├── 📄 jobposts.csv # Re-categorized job posts
│         └── 📁 base_results/
│              └── 📄 [LLM evaluation files] # LLM matching results
|                     (CVs ↔ job posts)
│
├── 📘 0_data_clean.ipynb # Load and explore raw CSVs
├── 📘 1_read_example.ipynb # data reading examples for workflow use
├── 📘 2_classify_job_posts.ipynb # re-categorize job posts using LLMs
├── 📘 3_base_LLM_match.ipynb # Baseline CV ↔ job post matching with LLM
├── 📘 4_advanced_LLM_match.ipynb # Advanced LLM matching techniques
└── 📘 5_human_eval.ipynb # Human benchmark of LLM results 
```


<br>

### **Dev setup**
Just like for Mandatory assignments 1 to 3, follow the Development Setup guide.

<br>

***

<br>

### **Datasets** 

- Job postings: kaggle/[PromptCloudHQ/us-jobs-on-monstercom](https://www.kaggle.com/datasets/PromptCloudHQ/us-jobs-on-monstercom)
- Resumes: huggingface/[opensporks/resumes](https://huggingface.co/datasets/opensporks/resumes)  