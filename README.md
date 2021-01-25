


  # VAIM

**This is the implementation of Variational Autoencoder Inverse Mapper: An End-to-End Deep Learning Framework for Inverse Problems (VAIM).**


## Requirements
The code is written in Python3 and requires the following libraries:
* numpy
* tensorflow==1.11.0
* keras==2.1.2


## Getting started
* Install the python libraries. (See [Requirements](https://github.com/ijcai2021/VAIM#requirements)).
* Download the code from GitHub:
```bash
git clone https://github.com/ijcai2021/VAIM
cd VAIM
```

* Run the python script:
``` bash
python3 VAIM.py
```
-By defaul the script will run the first toy example which is $\rm f(x) = x^2$
- To run another toy example change self.example variable in configuration.py script line 5

h<sub>&theta;</sub>(x) = &theta;<sub>o</sub> x + &theta;<sub>1</sub>x


* To see the jupyter notebbok demo go to VAIM_demo.ipynb 
