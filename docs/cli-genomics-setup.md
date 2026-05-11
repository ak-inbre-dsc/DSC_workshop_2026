---
title: "Module 2_3: Setup Data for ‘Introduction to the Command Line for Genomics’"
layout: page
permalink: /tutorials/cli-genomics-setup/
date: 2026-05-10
description: "Download and unpack the Data Carpentry shell_data files on your Google Cloud instance (or any Linux terminal)."
nav_order: 3
---

> These instructions prepare the **shell_data** directory used in the Software Carpentry *Introduction to the Command Line for Genomics* lesson. Follow them in any Linux terminal—including your Google Cloud instance.

---
## Before you begin:
If your instance is not yet powered up, start it following these steps
1. Navigate to **Agent Platform → Notebooks → Workbench**.
2. Make sure you're in the **Instances** view.
3. Select the checkbox next to your instance and click **Start**. Once the instance shows a green checkmark (you may need to refresh if this takes long), open **JupyterLab**.
4. Open a new **Terminal**
---

## 1 · Navigate to Your Home Directory
Always keep workshop data in a tidy location (e.g., `$HOME`).

```bash
cd ~    # jump to your home directory
```

---

## 2. Create a folder for your data files

```bash
mkdir shell_data
cd shell_data
```

---

## 3 · Download the dataset from a Google Cloud Storage Bucket
```bash
gcloud storage cp --recursive gs://data_workshop_cli/* .
```

You should see sub-folders called `sra_metadata/` and `untrimmed_fastq/` in your `shell_data` folder. 

## 4. The lesson starts in your home directory, so navigate back there
```bash
cd ~
```
---

You’re now ready for the lesson!
---

### Next steps
[Open the first lesson](https://datacarpentry.github.io/shell-genomics/01-introduction.html)

As we are working from Jupyter Lab on our Google Cloud instance, you can **skip the following sections**:
- **How to access the shell**
- **How to access the remote server**
- **Call-out** 
