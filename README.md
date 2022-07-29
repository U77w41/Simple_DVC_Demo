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

```bash
git init
```
```bash
dvc init
```
```bash
dvc add data_given/winequality.csv # For tracking the data
```
```bash
git add .
```
```bash
git commit -m "first commit"
```
```bash
git add . && git commit -m "Update README.md"  # For updating the README.md file
```
```bash
git remote add origin https://github.com/U77w41/Simple_DVC_Demo.git
```

```bash
git branch -M main
```
```bash
git push -u origin main
```

#### To update anything 
```bash
git add .
git commit -m "Update README.md"
git push -u origin main
```


#### Modify the params.yaml file

#### Inside the dvc.yaml file we will specify the stages
