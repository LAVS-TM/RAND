# RAND [![Profile][title-img]][profile]

[title-img]:https://img.shields.io/badge/-LAVS-blue
[profile]:https://github.com/LAVS-TM


RAND is a repository for a sport **dataset analysis** made with the language **R**. The analysis is done in `Projet_final_Lemonnier_Alexandre_Simonin_Victor.ipynb` with a dataset description, some **statistical analysis**, **visualisation**, a **PCA** (Principal Component Analysis ) and finally a **logistic regression**.


## Dataset

The dataset is here in `/data/decathlon.csv`. The dataset is made up of several quite different pieces of data. These represent the scores obtained by athletes in the **decathlon** event at the **Olympic Games** and at the **Decastar**, we have the scores of the 10 events as well as their ranking and their points.

<img src="https://github.com/Bictole/OCR/blob/master/Test_img/readme_images/interface.png" alt="Interface">


### Usage

```bash
make
./src/main
```

The trash files produced by the compilation could be removed by :

```bash
make clean
```

or

```bash
make properclean
```

## Interface

The interface is made with SDL 2.0, it's a really simple component that need to be refactored. Here is a diagram that demonstrate its usability.

<img src="https://github.com/Bictole/OCR/blob/master/Test_img/readme_images/interface.png" alt="Interface">

## Costs

<img src="https://github.com/Bictole/OCR/blob/master/Test_img/readme_images/costs.png" alt="The outrageous Costs">