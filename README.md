# CardioMetaEnsemble
State-of-the-art ensemble and meta-learning Python models for precise cardiovascular risk prediction. Features modular and reproducible pipelines, rigorous evaluation including ROC/AUC, and adaptable workflows for clinical dataset analysis and translational research applications.

## Notes

> This repository is shared for **peer-review purposes**.
>  
> The notebook represents the final, polished version of the CardioMetaEnsemble analysis, summarizing a much larger set of analyses and experiments conducted during the research process.
> 
> It provides all key results and workflows required to reproduce the main findings, while additional exploratory analyses, intermediate steps, and supplementary investigations from the research process are presented in a concise, condensed form.
>  
> License terms will be updated upon publication.

## Dataset

This repository uses a publicly available dataset:  

- **Heart Disease Dataset – Comprehensive**  
  Source: [IEEE DataPort](https://ieee-dataport.org/open-access/heart-disease-dataset-comprehensive)  
  Description: Description: This dataset combines five heart disease cohorts over 11 common features, which can be used to build predictive machine learning models for early-stage heart disease detection. Its use allows for benchmarking the performance of analytical methods against other studies conducted on the same dataset. 

## Files

- `CardioMetaEnsemble.ipynb` – Main Jupyter notebook implementing ensemble and meta-learning approaches  
- `README.md` – Project description and documentation  

## Usage

1. **Download the notebook**  
   Download `CardioMetaEnsemble.ipynb`.

2. **Download the dataset**  
   Download the **Heart Disease Dataset – Comprehensive** from IEEE DataPort.

3. **Provide the dataset to the notebook**  
   - **Option 1 (Recommended):** Place the dataset file in the **current working directory (cwd)** of the Jupyter Notebook.  
   - **Option 2:** Alternatively, specify the full path to your dataset by updating each of the six occurrences of the `file_path` variable in the notebook

4. **Run the notebook**  
   Open `CardioMetaEnsemble.ipynb` in Jupyter Notebook and execute all cells sequentially.

