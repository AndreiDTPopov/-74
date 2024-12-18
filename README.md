import pandas as pd

# Чтение Excel-файла
df_excel = pd.read_excel('Df.xlsx')

# Посмотреть первые 5 строк
print(df_excel.head())

# Посмотреть информацию о таблице
print(df_excel.info())

# Randomly sample 70% of your dataframe
df_percent = df_excel.sample(frac=0.7)

# Randomly sample 7 elements from your dataframe
df_elements = df_excel.sample(n=7)
print(df_elements)# -74
