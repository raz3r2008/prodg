
  
  # prodg
  <br>
<p align="center" fontstyle="verdana" fontsize="25"> I will teach you how to use adobe photoshop. 
  </p>
<li>
laser
  cannon
</li>

<select>
  <option value="volvo">Volvo</option>
  <option value="saab">Saab</option>
  <option value="mercedes">Mercedes</option>
  <option value="audi">Audi</option>
</select>
<br>
mnelson:Desktop mnelson$ cd ~/Desktop
<br>
mnelson:Desktop mnelson$ mkdir myproject
<br>
mnelson:Desktop mnelson$ cd myproject/
<br>
mnelson:myproject mnelson$ git commit -m "This is my first commit!"
[master (root-commit) b345d9a] This is my first commit!
 1 file changed, 1 insertion(+)
 create mode 100644 mnelson.txt
 <br>
 
SELECT MAX(Price) AS LargestPrice
FROM Products;


import numpy as np
import pandas as pd
import matplotlib.pyplot as plt
from keras.datasets import mnist
from keras.utils import to_categorical 
def getData(): Copy
def getData():
    (X_train, y_train), (X_test, y_test) = mnist.load_data()
    img_rows, img_cols = 28, 28     
    y_train = to_categorical(y_train, num_classes=10)
    y_test = to_categorical(y_test, num_classes=10) Copy
    X_train = X_train.reshape(X_train.shape[0], img_rows, img_cols, 1)
    X_test = X_test.reshape(X_test.shape[0], img_rows, img_cols, 1) 
    plt.imshow(X_train[0][:,:,0])
    plt.show() Copy
    return X_train, y_train, X_test, y_test
getData() 
import numpy as np import pandas as pd
import matplotlib.pyplot as plt
from keras.datasets import mnist
from keras.utils import to_categorical
def getData():
    (X_train, y_train), (X_test, y_test) = mnist.load_data()
    img_rows, img_cols = 28, 28
    y_train = to_categorical(y_train, num_classes=10)
    y_test = to_categorical(y_test, num_classes=10)
    X_train = X_train.reshape(X_train.shape[0], img_rows, img_cols, 1)
    X_test = X_test.reshape(X_test.shape[0], img_rows, img_cols, 1)
    plt.imshow(X_train[0][:,:,0])
    plt.show()
    return X_train, y_train, X_test, y_test

getData() Copy
