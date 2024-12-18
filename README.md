import pandas as pd


# Чтение Excel-файла
df_excel = pd.read_excel('Оценки.xlsx')

# Посмотреть первые 5 строк
print(df_excel.head())

# Посмотреть информацию о таблице
print(df_excel.info())







data = {'Имя': ['Nikita', 'Alina', 'Sirgey', 'lyonya'],
        'Возраст': [25, 30, 22, 28]}
df = pd.DataFrame(data)

print(df.tail(2))
