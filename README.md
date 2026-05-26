# 🧾 PeerJ-103 and PeerJ-200 Review Datasets

## 📘 Overview
This repository contains a **curated dataset of peer reviews** developed as part of a **funded research project under the supervision of Dr. Junaid Shuja**, Tenure Track Assistant Professor, Department of Computer Science, Southeast Missouri State University, USA.  
The dataset supports ongoing research exploring the differences between **human-written, generic, and AI-generated peer reviews** in scientific publishing.

## 📊 Dataset Description
We curated a dataset of peer reviews by extracting **103 human-written reviews** from scientific papers published on [PeerJ](https://peerj.com/), a peer-reviewed open-access journal.

To enable comparative analysis, two additional review sets were created:
- **103 Generic Reviews** — generated using the [Review Generator](https://philippe-fournier-viger.com/reviewgenerator/index.html) tool.  
- **103 AI-Generated Reviews** — produced using **DeepSeek** and **GPT-4o**, based on the corresponding original papers.

This results in a **tripartite dataset** containing:
- 103 authentic human-written reviews  
- 103 generic machine-generated reviews  
- 103 AI-generated reviews  

Together, these samples enable systematic research on linguistic, structural, and semantic distinctions between **human and AI-generated peer reviews**.

# 📊 PeerJ-400 Dataset

## 📘 Dataset Description
This repository also includes the **PeerJ-400 dataset**, which contains a larger collection of peer reviews curated for comparative analysis between **human-written** and **AI-generated reviews**.

The dataset includes:
- **200 Human-Written Reviews** — collected from published PeerJ articles
- **200 AI-Generated Reviews** — generated using modern large language models such as **DeepSeek** and **GPT-4o**

Unlike the PeerJ-103 dataset, the PeerJ-200 dataset does **not** include generic machine-generated reviews.
All files are provided in CSV format with consistent structure and annotations.

## 🗂️ Data Format
The dataset is provided in **CSV format** with the following structure:

| Column Name     | Description |
|------------------|-------------|
| **Article Title** | Title of the research paper associated with the review |
| **Abstract**      | Abstract of the original paper|
| **Review**        | Full text of the peer review |
| **Review Type**   | Indicates the type of review |

### Review Type Values
- `Human`
- `Generic` *(available only in peerj103 dataset)*
- `AI-Generated`

## 🧩 Funding and Supervision- 
This dataset was developed as part of a **funded research project: (GRFC, SEMO)** under the supervision of **Dr. Junaid Shuja**.

## ⚠️ Note
This dataset supports an **unpublished research paper** and may be updated following peer review or final publication.  
Please cite this repository appropriately if you use the dataset in any research or analysis.

## 📄 Citation
A formal citation will be provided after the related paper is published.  




