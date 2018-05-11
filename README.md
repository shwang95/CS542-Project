# CS542 Project

This is repository for project of CS542, Boston University.

## Prepare

The project is written in python 3, and tested on python 3.5.2.

### Dataset

Before using our program, please download and unzip the _Stanford Dog Dataset_. Here's the link to the dataset:

* labels.csv: https://www.kaggle.com/c/7327/download/labels.csv.zip
* sample_submission.csv: https://www.kaggle.com/c/7327/download/sample_submission.csv.zip
* test: https://www.kaggle.com/c/7327/download/test.zip
* train: https://www.kaggle.com/c/7327/download/train.zip

After unzip, make sure the files and folders are arranged in the following example:

```
$ tree
CS542-Project/
├── dog-breed-identification
│   ├── labels.csv
│   ├── sample_submission.csv
│   ├── test
│   │   ├── 000621fb3cbb32d8935728e48679680e.jpg
│   │   ├── ...
│   │   └── fffbff22c1f51e3dc80c4bf04089545b.jpg
│   └── train
│       ├── 000bec180eb18c7604dcecc8fe0dba07.jpg
│       ├── ...
│       └── fff43b07992508bc822f33d8ffd902ae.jpg
├── models.py
├── README.md
└── report.pdf

3 directories, 20583 files
```

### Libraries

Here's the python libraries and corresponding ```pip``` packages used in our project. Use ```pip install [package-name]``` to install all the libraries before using. Use ```sudo``` command if needed.

| Name | ```pip``` Package Name |
| --- | --- |
| Matplotlib | ```matplotlib``` |
| Numpy | ```numpy``` |
| Pandas | ```pandas``` |
| tqdm | ```tqdm``` |
| scikit-learn | ```scikit-learn``` |
| Keras | ```keras``` |

## Usage

```$ python models.py```

## Output

The program will output an array of images produced by ResNet-50 model as a sample result, and error rate and running time for each model. At end it will output some wrong prediction examples, and a total running time.
