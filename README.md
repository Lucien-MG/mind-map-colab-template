# 🧠 My Self-Hosted Mind Map Wiki

This repository contains a searchable wiki with interactive mind maps, automatically deployed via **GitHub Actions** and hosted on **GitHub Pages**.

## 🚀 Setup Instructions

Follow these **3 steps** to get your wiki live:

### 1. Configure GitHub Permissions (Crucial)
GitHub Actions need permission to create the website branch for you.
1. Go to your repository **Settings**.
2. On the left sidebar, click **Actions** > **General**.
3. Scroll down to **Workflow permissions**.
4. Select **"Read and write permissions"**.
5. Click **Save**.

### 2. Verify Repository Structure
Ensure your files are organized exactly like this:
```text
.
├── .github/workflows/deploy.yml  
├── docs/
│   ├── index.md                  
│   └── roadmap.md                
├── mkdocs.yml                    
└── requirements.txt
