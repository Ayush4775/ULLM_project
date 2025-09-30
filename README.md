
# Understanding Language Models Project
In this project probing experiments to investigate the internal representation of the BERT transformer model of logical problems is conducted. A new dataset is created.  

---
## Project Structure

```bash
.
├── Datasets/
    ├── reasoning_patterns_dataset.csv          # In-distribution
    ├── reasoning_patterns_test_whenever.csv    # Out-of-distribution
├── Figures/
    ├── accuracy_in_distribution.pdf            # In-distribution
    ├── accuracy_out_of_distribution.pdf        # Out-of-distribution
├── dataset_creation.ipynb
├── probing_experiments.ipynb
├── requirements.txt
└── README.md               
```

---

The datasets were created using `dataset_creation.ipynb`. Please note that rerunning the script will lead to different datasets (but with the same structure), due to the stochastic nature of the process. The exact datasets that we used for all experiments, can be found in `Datasets/`.

We conducted the experiments in `probing_experiments.ipynb`. Here the necessary code, including the calculated accuracy values and created figures, can be found and used to rerun the experiment. To rerun the experiment please use `requirements.txt`to install all necessary Python packages. A `.pdf` version of the figures can additionally be found in `Figures/`.

