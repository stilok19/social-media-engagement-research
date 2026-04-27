# social-media-engagement-research

End-to-end multimodal deep learning pipeline analyzing social media posts combining GCP Vision API and BERTweet for fast food brand engagement research

## Architecture

## Tech Stack
| Layer | Tool |
|-------|------|
| Data Lake | Google Cloud Storage |
| Data Warehouse | BigQuery |
| Transforms | dbt Core |
| ML | Python + VS Code |
| Dashboard | Looker Studio |
| Version Control | GitHub |

## Setup

### 1. GCP Setup
```bash
bash setup_gcp.sh
```

### 2. Project Setup
```bash
bash setup_project.sh
```

### 3. Activate Environment
```bash
source ~/social-media-engagement-research-env/bin/activate
```

## Author
May Tilokruangchai