## HW6
# Завдання 1
У цьому завданні вам потрібно завантажити [цей](https://www.kaggle.com/datasets/sootersaalu/amazon-top-50-bestselling-books-2009-2019?resource=download) датасет. Ми з вами вже працювали з ним коли вивчали pandas. Це все так само Топ-50 книг, що найбільше продаються на Amazon в період з 2009 по 2019 роки. Потрібно виконати таке:
1. Створити спарк сесію.
2. Прочитати датасет до датафрейму.
3. Використовуючи тільки RDD обчислити середню ціну всіх книг, у яких рейтинг вищий за 4.7
4. Побудувати гістограму розподілу рецензій (стовпець Reviews).
5. Побудувати матрицю кореляції для стовпців "User Rating", "Reviews" та "Price".
6. Використовуючи бібліотеку seaborn побудувати парні графіки (pairplots) стовпців "User Rating", "Reviews" та "Price".

# Завдання 2
Під час виконання цього завдання можна використовувати лише Spark SQL. Для датасету з попереднього завдання виконайте таке:
1. Знайдіть автора із найвищим рейтингом.
2. Знайдіть трьох авторів із найнижчим рейтингом.
3. Визначте, який автор отримав найбільшу кількість рецензій.
4. Визначте, який автор написав найбільшу кількість книг за весь доступний у даних період.
5. Визначте, яка книга жанру "Fiction" має найменший рейтинг.
6. Визначте, яка книга жанру "Non Fiction" має найвищий рейтинг.

# Завдання 3
Побудуйте гістограму середньої кількості рецензій за роками. У вигляді окремої гістограми візуалізуйте кількість книг жанру "Fiction" та "Non Fiction" за весь доступний період.

# Завдання 4 (за бажанням)
Спробуйте портувати код, написаний вами раніше під pandas датафрейми на спарк датафрейми.
