import matplotlib.pyplot as plt
import numpy as np
import pandas as pd

gra = {
"a" : pd.Series([130 ,1900, 16.3], index = ["HP", "Wieghts", "Gasoline Mileage"]),
"b" : pd.Series([250, 2600, 10.2], index = ["HP", "Wieghts", "Gasoline Mileage"]),
"c" : pd.Series([190, 2200, 11.1], index = ["HP", "Wieghts", "Gasoline Mileage"]),
"d" : pd.Series([300, 2900, 7.1], index = ["HP", "Wieghts", "Gasoline Mileage"]),
"e" : pd.Series([210, 2400, 12.1], index = ["HP", "Wieghts", "Gasoline Mileage"]),
"f" : pd.Series([220, 2300, 13.2], index = ["HP", "Wieghts", "Gasoline Mileage"]),
"g" : pd.Series([170, 2100, 14.2], index = ["HP", "Wieghts", "Gasoline Mileage"]) }

df =pd.DataFrame(gra)
df
