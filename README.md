# Backdoor-attack-ML-in-cybersec-Lab3

```
Models
 |__ 2_percent.h5
 |__ 4_percent.h5
 |__ 10_percent.h5
Reports
 |__ df_acc_after_each_prune.csv
 |__ df_attack_success_rates.csv
Lab3.ipynb
Eval_and_good_model.ipynb
```

## Description

#### ```Lab3.ipynb``` contains all the required code. (Pruning, evaluation on test images and building good model)
#### ```Eval_and_good_model.ipynb``` contains code to use ```eval.py``` script to test repaired models and evaluate good models.
#### ```Models``` directory contains 3 repaired networks where accuracy drops 2,4 and 10 respectively.
#### ```Reports``` Accuracies and rate of attacks after each prune

## Evaluating repaired networks using ```Eval.py``` in ```CSAW-HackML-2020/lab3/```

#### 2 percent drop:
```
python CSAW-HackML-2020/lab3/eval.py CSAW-HackML-2020/lab3/data/cl/test.h5 /content/CSAW-HackML-2020/lab3/data/bd/bd_test.h5 mycyb-lab3-models/2_percent.h5
```


#### 2 percent drop:
```
python CSAW-HackML-2020/lab3/eval.py CSAW-HackML-2020/lab3/data/cl/test.h5 /content/CSAW-HackML-2020/lab3/data/bd/bd_test.h5 mycyb-lab3-models/2_percent.h5
```

#### 2 percent drop:
```
python CSAW-HackML-2020/lab3/eval.py CSAW-HackML-2020/lab3/data/cl/test.h5 /content/CSAW-HackML-2020/lab3/data/bd/bd_test.h5 mycyb-lab3-models/2_percent.h5
```

## Evaluating good model

#### Run the Goodnet section of ```Eval_and_good_model.ipynb```
