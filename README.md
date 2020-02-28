# Welcome to proba_lib
> Documentation about a few probability fuctions as expected value, variance, covariance, etc. Just for testing purposes.


This file will become your README and also the index of your documentation.

## Install

for the following functions you'll need to have math and numpy libraries.

`pip install proba_lib` <br> `pip install numpy` <br> `pip install math`

## How to use

### An example function:

```
def expected_value(a,X):
    return np.mean((a.dot(X)))
```

```
print("Expected value x:", str(expected_value(np.array([1,2,3]),np.array([0.6,0.3,0.2]))))
```

    Expected value x: 1.8

