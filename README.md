# Steps


create env

```bash
conda create -n wineq python=3.10 -y
```

activate env
```bash
conda activate wineq
```

create requirements.txt

install requirements.txt
```bash
pip install -r requirements.txt
```

Download the data from
https://www.kaggle.com/datasets/aleixdorca/wine-quality

git init

dvc init

dvc add data_given/winequality.csv # For tracking the data

git add .

git commit -m "first commit"