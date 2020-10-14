# Tensforflow day1


1. 인공신경망
2. Anaconda + Tensorflow 환경, Google codelab
3. 퍼셉트론(뉴론) 이해

## Anaconda

1. [conda 시작](https://docs.conda.io/projects/conda/en/latest/user-guide/getting-started.html)

```sh
conda --version
conda update conda
```
#### Managing environ

```
$conda create --name snowflakes biopython
$conda activate snowflakes
(snowflakes) $
```


```sh
(snowflakes)$ conda info --envs
A list of environments appears, similar to the following:

conda environments:

    base           /home/username/Anaconda3
    snowflakes   * /home/username/Anaconda3/envs/snowflakes
```

가상환경 삭제

```sh
$ conda env remove -n snowflakes --all
```

#### Python 버전

```sh
$ conda create --name snakes python=3.5
```


#### package

```sh
$ conda search beautifulsoup4
$ conda install beautifulsoup4
$ conda list
```
