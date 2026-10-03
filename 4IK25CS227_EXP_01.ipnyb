import numpy as np
import pandas as pd

arr = np.array([2, 4, 6, 8, 10, 12, 100, 50])

print("Array : ", arr)
print("Mean : ", arr.mean())
print("Variance : ",arr.var())
print("\nReshaped Array : ", arr.reshape(4,2))
print("\nSliced (from 1 to 3) : ", arr[1:4])

students = {
    "name": ["Alice", "Bob", "Charlie", "David","Thejaswi"],
    "marks": [85, 90, 78, 92, 98],
    "branch": ["CSE", "ECE", "ME", "CSE", None]
}

df = pd.DataFrame(students)
print("Student Dataset :\n")
print(df)
print("\nMarks :\n", df["marks"])
print("\nSliced Dataset :(0 to 3)\n", df.iloc[0:3])
print("\nStudents with marks > 80 :\n", df[df["marks"] > 80])
print("\nDescription : \n",df.describe())
print("\nDuplicates : \n",df.duplicated())
print("\n",df.isnull().sum())