# ML_estimation
This project implements a GMM_ML_estimation algorithm for estimating the probability distribution of a dataset. The program reads an input data file x.csv, calculates posterior probabilities z and variational parameters params based on the specified parameter k, and outputs the result files z.csv and params.dat, along with generating a corresponding 3D plot.<br><br>

### This project requires the following Python libraries:<br>
-numpy<br>
-scipy<br>
-pandas<br>
-matplotlib<br>
### You can install these libraries using the following command:<br>
```python
pip install numpy scipy pandas matplotlib
```
### Run the following command in the terminal(Here 4 means K=4) ：<br>
```python
python main.py x.csv z.csv params.dat 4
```
<br>
where x.csv is the input data file, z.csv is the posterior probability output file, params.dat is the variational parameters output file, and 4 is the specified k value.
The program will output the z.csv and params.dat files and display the corresponding 3D plot.<br><br>

$${\color{red}Please \space try \space  changing \space  the\space k \space value\space \color{blue}To \space observe \space different\color{orange} \space results！}$$


# VB_estimation
This project implements a VB_estimation algorithm for estimating the probability distribution of a dataset. The program reads an input data file x.csv, calculates posterior probabilities z and variational parameters params based on the specified parameter k, and outputs the result files z.csv and params.dat, along with generating a corresponding 3D plot.<br><br>
### This project requires the following Python libraries:<br>
-numpy<br>
-scipy<br>
-pandas<br>
-matplotlib<br>
-fire<br>

### You can install these libraries using the following command:<br>
```python
pip install numpy scipy pandas matplotlib fire
```

### Run the following command in the terminal(Here 4 means K=4)：<br>
```python
python main.py x.csv 4
```
<br>
where x.csv is the input data file, z.csv is the posterior probability output file, params.dat is the variational parameters output file, and 4 is the specified k value. The program will output the z.csv and params.dat files and display the corresponding 3D plot.<br>

$${\color{red}Please \space try \space  changing \space  the\space k \space value\space \color{blue}To \space observe \space different\color{orange} \space results！}$$




