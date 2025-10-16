# EXNO-6-DS-DATA VISUALIZATION USING SEABORN LIBRARY

# Aim:
  To Perform Data Visualization using seaborn python library for the given datas.

# EXPLANATION:
Data visualization is the graphical representation of information and data. By using visual elements like charts, graphs, and maps, data visualization tools provide an accessible way to see and understand trends, outliers, and patterns in data.

# Algorithm:
STEP 1:Include the necessary Library.

STEP 2:Read the given Data.

STEP 3:Apply data visualization techniques to identify the patterns of the data.

STEP 4:Apply the various data visualization tools wherever necessary.

STEP 5:Include Necessary parameters in each functions.

# Coding and Output:
```
import pandas as pd
import numpy as np
import seaborn as sns
import matplotlib.pyplot as plt
x = [1, 2, 3, 4, 5]
y = [3, 6, 2, 7, 1]
sns.lineplot(x=x,y=y)
plt.xlabel('X-axis')
plt.ylabel('Y-axis')
plt.show()
```

<img width="1027" height="693" alt="Screenshot 2025-10-16 171936" src="https://github.com/user-attachments/assets/3c1bc757-cb42-4b67-8738-5b8a6c7b47f6" /> 

```
x = [1, 2, 3, 4, 5]
y1 = [3, 5, 2, 6, 1]
y2 = [1, 6, 4, 3, 8]
y3 = [5, 2, 7, 1, 4]
sns.lineplot(x=x,y=y1)
sns.lineplot(x=x,y=y2)
sns.lineplot(x=x,y=y3)
plt.xlabel('X-axis')
plt.ylabel('Y-axis')
plt.show() 
```

<img width="1226" height="655" alt="Screenshot 2025-10-16 172058" src="https://github.com/user-attachments/assets/b5eed9f5-f694-4884-b029-f587026e20b5" />

```
import seaborn as sns
import matplotlib.pyplot as plt
data = [55, 60, 65, 70, 75, 80, 85, 90, 95, 100, 70, 75, 80, 85, 90, 95, 100]
sns.histplot(data, bins=8, kde=True, color='skyblue')
plt.title('Distribution of Exam Scores')
plt.xlabel('Score')
plt.ylabel('Frequency')
plt.show()
```

<img width="1100" height="711" alt="Screenshot 2025-10-16 172240" src="https://github.com/user-attachments/assets/980ee60e-932a-4c6c-b654-e36dbe0dcd8c" /> 
```
import seaborn as sns
import matplotlib.pyplot as plt
tips = sns.load_dataset("tips")
sns.scatterplot(data=tips, x="total_bill", y="tip", hue="sex", style="time")
plt.title("Tip vs Total Bill")
plt.xlabel("Total Bill ($)")
plt.ylabel("Tip ($)")
plt.show() 
```

<img width="1108" height="697" alt="Screenshot 2025-10-16 172438" src="https://github.com/user-attachments/assets/9187ad10-fb5e-4595-adb3-c6a67cc095b1" /> 

```
import seaborn as sns
import matplotlib.pyplot as plt
tips = sns.load_dataset("tips")
sns.violinplot(data=tips, x="day", y="total_bill", hue="sex", split=True)
plt.title("Distribution of Total Bill by Day and Sex")
plt.show()
```

<img width="1181" height="717" alt="Screenshot 2025-10-16 172548" src="https://github.com/user-attachments/assets/fead2265-eaa4-406c-8326-392b8f9f200d" />

```
import seaborn as sns
import matplotlib.pyplot as plt
iris = sns.load_dataset("iris")
sns.kdeplot(data=iris, x="sepal_length", fill=True, color="skyblue", linewidth=2)
plt.title("KDE Plot of Sepal Length")
plt.xlabel("Sepal Length")
plt.ylabel("Density")
plt.show()
```

<img width="1197" height="721" alt="Screenshot 2025-10-16 172650" src="https://github.com/user-attachments/assets/f2d0cdb5-69f0-445b-b0ce-38a518bd8d50" />



# Result:
 we Perform Data Visualization using seaborn python library for the given datas.

