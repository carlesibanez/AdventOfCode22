# AdventOfCode22

This repo contains my code to solve the [2022 Advent of Code](https://adventofcode.com/2022). The solutions are implemented in Python and tested in a virtual environment on Python 3.8.10. 

## Repo structure

The project structure is as follows:

```bash
├── inputs
│   ├── adventofcode.com_2022_day_01_input.txt
│   ├── adventofcode.com_2022_day_02_input.txt
│   └── ...
├── requirements.txt
└── src
    ├── Day01.ipynb
    ├── Day02.ipynb
    └── ...
```

The contents of the two folders are the following:

* The [inputs](./inputs/) folder contains the inputs I got from the advent of code, for which the solutions are presented down below. The format of the input files names is adventofcode.com_2022_day_**00**_input.txt, where 00 stands for the day number in two digit format. 
* The [src](./src/) folder contains a Jupyter notebook for each day of the calendar, with the code to solve eache day's problem. The format of the notebook names is Day**00**.ipynb where 00 is the day number in two digit format, e.g. solution for day 1 is in [src/Day01.ipynb](./src/Day01.ipynb).


## Replicability

To replicate the environment, you need to install the packages from the [requirements.txt](./requirements.txt) file. Once cloned the repo, navigate to the root of the project and do as follows:

```
python -m venv venv
source venv/bin/activate
python -m pip install -r requirements.txt
```

## Solutions

The solutions for the 25 puzzles, both parts are shown in the table below:

|       | Part 1    | Part 2 |
|---    | -------- | ------- |
|Day 1  | 68442    | 204837  |
|Day 2  | 13924    | 13448   |
|Day 3  | 7691     | 2508    |
|Day 4  | 602      | 891     |
|Day 5  | BWNCQRMDB| NHWZCBNBF  |
|Day 6  | 1080     | 3645    |
|Day 7  | 1844187  | 4978279 |
|Day 8  | 1812     | 315495  |
|Day 9  | 5735     | 2478    |
|Day 10 | 14920    | BUCACBUZ|
|Day 11 | 54253    | 13119526120 |
|Day 12 | 468      | 459     |
|Day 13 | 6420     | 22000   |
|Day 14 | 795      | 30214    |
|Day 15 | 4737443  | 11482462818989 |
|Day 16 | 1460     | 2117    |
|Day 17 | 3161     | 1575931232076  |
|Day 18 | 3500     | 2048    |
|Day 19 | 1115     | 25056   |
|Day 20 | 1591     | 14579387544492 |
|Day 21 | 10037517593724 | 3272260914328 |
|Day 22 | 162186   | 55267   |
|Day 23 | 4172     | 942     |
|Day 24 | 295      | 851     |
|Day 25 | 2=222-2---22=1=--1-2     |     |

