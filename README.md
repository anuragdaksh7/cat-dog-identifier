# cat-dot-identifier

### A sequential CNN which can tell cat and dog apart

This model was trained on [Cat--VS--Dogs](https://www.kaggle.com/datasets/pybear/cats-vs-dogs) dataset from kaggle

Link to the [pretrained model](https://drive.google.com/file/d/1I51epIYxm8YYtGp4rY06yZjSV4uPLQET/view?usp=sharing)

## Steps for installation
- $ git clone this repo
- download the dataset from given website
- extract the dataset
- replace path in the file with your path to petimages folder
- now open jupyter notebook
- open this file using jupyter notebook
- run the cells in the sequence they are in.

## Installing Jupyter Notebook
- $ pip install notebook <- this would install jupyter notebook
- $ jupyter notebook <- this would start notebook in local server

## Details about model

Layer | Shape | Params
--- |--- |---
Conv2D | (None, 98, 98, 32) | 896
MaxPooling2D | (None, 49, 49, 32) | 0
Conv2D | (None, 47, 47, 64) | 18496
MaxPooling2D | (None, 23, 23, 64) | 0
Flattenn | (None, 33856) | 0
Dense | (None, 64) | 2166848
Dense | (None, 1) | 65


## Graphs
- ![image](https://github.com/anuragdaksh7/cat-dog-identifier/assets/84393491/5fcc05c9-d859-4f62-a118-358d86a6e711)
- ![image](https://github.com/anuragdaksh7/cat-dog-identifier/assets/84393491/c1e661fe-7763-4851-acf3-740ef6a8e56f)

