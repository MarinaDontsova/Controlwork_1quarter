# Controlwork_1quarter 
## Контрольная работа по итогам первой четверти


1. *Создала репозиторий на Github под названием Controlwork_1quarter* и склонировала его на свой компьютер для дальнейшей работы (команда git clone). Создала файл .gitignore

2. *Блок-схема решения задачи* - в отдельном файле. 

3. ## _Условие задачи_ ##
    Написать программу, которая из имеющегося массива строк формирует массив строк, длина которых меньше либо равна 3 символа. Первоначальный массив можно ввести с клавиатуры, либо задать на старте выполнения алгоритма. При решении не рекомендуется пользоваться коллекциями, лучше обойтись исключительно массивами.

4. *Решение задачи*:

    4.1. Берем первый элемент исходного массива и проверяем длину символов элемента. 

    4.2. Если количество символов элемента меньше или равно 3, то этот элемент массива отправляем в новый создаваемый массив (п.4.3). Если длина символов элемента больше 3, то переходим к проверке следующего элемента массива (п.4.4). 

    4.3. Записываем элемент в новый массив.
   
    4.4. Берем следующий элемент исходного массива и проверяем длину символов элемента. Если элементы в исходном массиве закончились, то выводим на печать новый массив (переходим к п.4.7).

    4.5. Если длина символов элементов меньше или равно 3, то переходим к п.4.3. Если длина символов элемента больше 3, то переходим к п.4.4.

    4.6. Записываем элемент в новый массив и переходим к п.4.4. (Цикл).
    
    4.7. Выводим на экран вновь созданный массив строк.