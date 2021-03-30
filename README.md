# Практическое задание на тему File Handling


#### 1. Напишите программу Python для ввода числа, если это не число, сгенерируйте сообщение об ошибке, введите другой ввод, пока не будет целое число
           | Input | OUTPUT |
           |  ---  |  ---  |
           | abc | This not a number |
           | a1w | This not a number |
           | 111l | This not a number |
           | 2 | number |
#### 2. Напишите программу Python, которая принимает текстовый файл в качестве входных данных и возвращает количество слов в заданном текстовом файле.
#### Примечание. Некоторые слова можно разделять запятой без пробела.

#### DATA.txt содержит
           -Lorem Ipsum является текст-заполнитель обычно используется в графических,печать и издательской индустрии для предварительного просмотра макета и визуальных  макетах.

| File | OUTPUT |
|   ---   | --- |
| количество слов в DATA.txt | 19 |


#### 3. Напишите программу Python, которая открывает файл с фотографией и создаёт новый файл с тем же рисунком.
     ##### перед запуском кода
     -PythonProject
           -w211.jpg
           
     ##### после запуска кода
     -PythonProject
           -w211.jpg
           -w212.jpg
          
                    


#### 4. Напишите простую программу Python, используя принцип ООП, для выполнения некоторых простых банковских операций, таких как просмотр баланса, внесение денег, снятие денег, отправка денег. 
#### При снятие и отправка денег есть комиссия в размере 1% суммы транзакции. После каждой транзакции должна создаться .txt файл ввиде чека который информацию про транзакция выполнелось, текущую сумму карты и **время транзакции.

      -Добро пожаловать в банкомат Академии
      -Выберите операцию который вы хотите сделать:
      - 1. просмотр баланса 2.внесение денег 3. снятие денег 4. отправка денег 0. Завершить оперпцию
      - :2 
      -Введите сумму для депозита:
      -Внесенная сумма: 1000.0
      - 1. просмотр баланса 2.внесение денег 3. снятие денег 4. отправка денег 0. Завершить оперпцию
      - :3
      -Введите сумму вывода: 500.0
      -Вы сняли: 500.0
      - 1. просмотр баланса 2.внесение денег 3. снятие денег 4. отправка денег 0. Завершить оперпцию
      - :1
      -Текущий баланс = 500.0
      - 1. просмотр баланса 2.внесение денег 3. снятие денег 4. отправка денег 0. Завершить оперпцию
      - :4
      - Введите Банковский аккаунт получателя карты: 8600435786541232
      - Введите сумму отправки: 500.0
      - Вы отправили: 500.0
      - 1. просмотр баланса 2.внесение денег 3. снятие денег 4. отправка денег 0. Завершить оперпцию
      - :5
      - Спасибо за выбор банкомат Академии
      
      
