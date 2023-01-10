# Submission  Reproduction

To reproduce the submission, follow the instructions below to reconstruct the environment.

1. [Download necessary packages](#Download-necessary-packages)
2. [Download the model weight](#Download-the-model-weight)
3. [Download the datasets](#Download-the-datasets)

## Download necessary packages
To download the necessary Python packages, simply run `pip install -r requirement.txt` in this repo.

## Download the model weight
Download the [models.zip](https://drive.google.com/open?id=10EaRD58y6gF8YA688_sPbVz06xOMk7YH&authuser=0&usp=drive_link) file and unzip it.

If you have gdown in your environment (and you should probably do from the first step), run the following script:
```bash=
$ gdown 10EaRD58y6gF8YA688_sPbVz06xOMk7YH
$ unzip models.zip
```

## Download the datasets
Download the dataset of the competition from [here](https://www.kaggle.com/competitions/tabular-playground-series-aug-2022/data) and unzip it.

---

After you've done the steps above, make sure you have the directory structure below:
```
.
├── model0.h5
├── model1.h5
├── model2.h5
├── model3.h5
├── model4.h5
├── model5.h5
├── model6.h5
├── model7.h5
├── model8.h5
├── model9.h5
├── models.zip
├── sample_submission.csv
├── tabular-playground-series-aug-2022.zip
├── test.csv
└── train.csv
```

If you have all the files above ready, open up the inference file [109550162_Final_inference.ipynb](https://github.com/Lucas-Kuo/111Fall_ML_Final/blob/main/109550162_Final_inference.ipynb) and start running the cells from the second section where it says
> **Start from here if your running this notebook in other environments**

After running all cells, you should have the final submission file named `submission_final.csv` under the same directory, which should give you the exact same result score given in the final section of my report.
