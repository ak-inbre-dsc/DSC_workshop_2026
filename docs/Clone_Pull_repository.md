
# Important! 

> ## If your instance DOES NOT CONTAIN the dsc_workshop_2026 folder in the home directory, do ONLY section A and C.  

> ## If your instance CONTAINS the dsc_workshop_2026 folder in the home directory, do ONLY section B and C.

--- 

## Section A: Clone the workshop Git repository

### GUI method 

1. In the top menu, choose **Git → Clone a Repository…**  
2. Paste `https://github.com/ak-inbre-dsc/dsc_workshop_2026.git` and click **Clone**.  
3. The repo appears in the file browser inside `~/dsc_workshop_2026/`.

### Terminal alternative

```bash
cd ~
git clone https://github.com/ak-inbre-dsc/dsc_workshop_2026.git
```

---

## Section B: Pull the latest changes from the Github repository

### GUI method 

1. Navigate to your dsc_workshop_2026 directory
2. In the top menu, choose **Git → Pull from Remote**

### Terminal alternative

```bash
cd ~/dsc_workshop_2026
git pull
```


## Section C: Work through the workshop notebooks

Open the **`notebooks/Git`** folder inside the cloned repo and run the notebooks **in this order**:

| # | Notebook                                  
|---|---------------------------------------------|
| 1 | `DSC_Module_3_Lesson1_Git.ipynb`           
| 2 | `DSC_Module_3_Lesson2_Git_and_Github.ipynb`  
| 3 | `DSC_Module_3_Lesson3_Collaborating_Collaborator1.ipynb / DSC_Module_3_Lesson3_Collaborating_Collaborator2.ipynb`   
| 2 | `DSC_Module_3_Lesson4_RStudioServer_Git.ipynb`  

