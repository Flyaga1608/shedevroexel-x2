import pandas as pd


# Чтение Excel-файла
df_excel = pd.read_excel('Оценки.xlsx')

# Посмотреть первые 5 строк
print(df_excel.head())

# Посмотреть информацию о таблице
print(df_excel.info())








import pandas as pd

data = {
    'Имя': ['Nikita', 'Kostya', 'Alina', 'lyohya'],
    'Возраст': [18, 37, 21, 24],
    'Город': ['Moscow', 'Saint-Petersburg', 'Novosibirsk', 'Krasnoyarsk']
}
df = pd.DataFrame(data)

selected_columns = ['Имя', 'Город']
result_df = df[selected_columns]
print(result_df)
