# Machine Learning

## Workshops

* \*\*\*\*[**IML - HEP ML Resource list**](https://github.com/iml-wg/HEP-ML-Resources)\*\*\*\*
* [Fifth Machine Learning in High Energy Physics Summer School 2019](https://indico.cern.ch/event/768915/timetable/?view=standard)

## ML with ROOT packages

### TMVA

* [TMVA tutorial](https://github.com/lmoneta/tmva-tutorial)

## ML with Python packages

Here I used Mac OS to setup the environment for the machine learning \(ML\) packages with Python. 

### Install Python3

Mostly ML packages work with Python3. We have several ways to install Python3. We could use Anaconda to install, but here I will directly install the official Python3 in the website of Python. You can also follow the instruction [here](https://realpython.com/installing-python), which provide the installation of Python with command line. 

In this tutorial, I use Python 3.6.8.

### Install Tensorflow

```text
pip3 install tensorflow
```

### Install Keras

For python3

```text
pip3 install keras
```

### Pandas

```text
pip3 install pandas
```

### Theano

```text
pip3 install theano
```

### Sklearn

```text
pip3 install sklearn
```

### Xgboost

```text
pip3 install xgboost
```

If you encounter problem, you can build xgboost with the repository 

```text
brew install gcc@7
```

```text
git clone --recursive https://github.com/dmlc/xgboost
```

```text
mkdir build
cd build
CC=gcc-7 CXX=g++-7 cmake ../xgboost
make -j4
```

```text
# in xgboost folder
cd python-package; sudo python3 setup.py install
```

{% code title="~/.bashrc" %}
```bash
export PYTHONPATH=path-to-xgboost/xgboost/python-package
```
{% endcode %}

## Troubleshooting

#### 

