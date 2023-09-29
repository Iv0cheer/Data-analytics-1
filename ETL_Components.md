# **Practice 3**

## Task:
![image](https://github.com/Iv0cheer/Data-analytics-1/assets/112684546/ed0118ae-dd42-45bc-8d7a-6d435ba87c2a)



### Вариант исполнения схемы:
![image](https://github.com/Iv0cheer/Data-analytics-1/assets/112684546/e64d9fde-f45e-4ef7-b986-81c9a984ee55)



### Solution (components):

- **CSV file input**

![image](https://github.com/Iv0cheer/Data-analytics-1/assets/112684546/32f0c187-bd14-4f26-a4b8-cbdf8f5f4d81)

Самый стандартный загрузчик файлов с форматом "CSV". Позволяет загрузить файл с указанным форматом в Workspace.


- **Delete**

![image](https://github.com/Iv0cheer/Data-analytics-1/assets/112684546/de3fcc52-6c88-4d96-aef8-6baee29efd4b)

Является модулем выгрузки данных, в данном случае удаляет выходные данные.


- **Automatic documentation output**

![image](https://github.com/Iv0cheer/Data-analytics-1/assets/112684546/f295b510-15fd-41a3-b1c2-ba872a32db38)

На основе входных (а в дальнейшем и выходных) данных формирует документацию в виде списка преобразований.


- **Insert / Update**

![image](https://github.com/Iv0cheer/Data-analytics-1/assets/112684546/8d441fd8-6fa1-4845-8be8-942ac2fd272c)

Обновляет или вставляет строки в базу данных, распределенную по ключам.


- **JSON Output**

![image](https://github.com/Iv0cheer/Data-analytics-1/assets/112684546/53121fe5-c2a4-4445-976d-a6396d6117df)

Стандартный вывод получившихся данных в файл с расширением *.json формата "ключ-значение".


- **Unique rows**

![image](https://github.com/Iv0cheer/Data-analytics-1/assets/112684546/7d033634-a4c7-4ad1-b801-b22e60b3b59b)

Удаляет повторяющиеся строки и оставляет только одно уникальное совпадение (один раз). Работает только с фильтрованными (сортированными) входными данными, в ином случае - обрабатываются только двойные последовательные строки.


- **Set field value**

![image](https://github.com/Iv0cheer/Data-analytics-1/assets/112684546/358d29b2-60c4-4c46-8021-d50dbb111b30)

Устанавливает в конкретное поле БД конкретное значение.


- **Sort rows**

![image](https://github.com/Iv0cheer/Data-analytics-1/assets/112684546/4c12bf18-fc08-4c96-8497-c9de6ae224c9)

Сортирует строки по тому или иному признаку в БД (как на увеличение, так и на убывание)


- **Clone row**

![image](https://github.com/Iv0cheer/Data-analytics-1/assets/112684546/13963192-26f7-4a76-ad0f-6dcc74030373)

Копирует конкретный кортеж (строку) столько раз, сколько запросит пользователь.


- **Merge join**

![image](https://github.com/Iv0cheer/Data-analytics-1/assets/112684546/a64678aa-ee54-483d-bc0e-87cf366f2ead)

Объединяет два потока по заданному ключу и выдает объединенный набор. Входные потоки должны быть отсортированны по первичному ключу.


- **Set variables**

![image](https://github.com/Iv0cheer/Data-analytics-1/assets/112684546/8dbdee5d-5749-43f2-9ae8-c94a0e99b362)

Устанавливает одну и более переменных.


- **Split fields**

![image](https://github.com/Iv0cheer/Data-analytics-1/assets/112684546/7f8c9276-b644-4b49-bd5b-0031444a352b)

Разделяет одно поле на несколько.
