# series_creation
import pandas as pd
import numpy as np
from numpy import random
# Series Creation
ser1 = pd.Series(data=random.randint(10,45,size=5),index=['a','b','c','d','e'])
print("Series is")
print(ser1)
