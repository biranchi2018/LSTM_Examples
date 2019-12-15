
LSTM Array Shapes :
=====================

```
One to one single feature:
X = array(X).reshape(25, 1, 1)


One to one multiple feature:
X = array(X).reshape(25, 1, 2)


Many to one single feature:
X = X.reshape(15,3,1)


Many to one multiple feature:
X = X.reshape(15,3,2)

```

