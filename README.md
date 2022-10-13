Large numbers Practic #1
=====

# Задача
1. Використовуючи одну з існуючих бібліотек вивести кількість варіантів ключів, які можна задати 8-,16-,32-,64-,128-, 256-, 512- , 1024-, 2048-, 4096-бітною послідовністю.  
2. Для кожного з варіантів необхідно згенерувати випадкове значення ключа, яке знаходиться в діапазоні 0x00…0 до 0xFF…F залежно від обраної довжини ключа.  
3. Написати функцію для брутфорсу значень з діапазону з метою знаходження ключа. Мета функції перебирати значення ключа від 0x00 ... 0 до тих пір, поки буде не знайдено значення, рівне попередньо згенерованого ключового. Функція повинна виводити кількість часу в мілісекундах, яка була витрачена для знаходження ключа.  

Особливості щодо запуску/компіляції
-----
1. Функція GetNumberOfUniKeys() виводить кількість варіантів ключів, які можна задати 8-,16-,32-,64-,128-, 256-, 512- , 1024-, 2048-, 4096-бітною послідовністю.  
2. Функція GetRandomKeys() виводить випадковий ключ в діапазоні 0x00…0 до 0xFF…F залежно від довжини ключа.  
3. Функція BruteForceTime(size: int) виводить час у мілісекундах потрібний для знаходження ключа розміру заданого аргументом.  
