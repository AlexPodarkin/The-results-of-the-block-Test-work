  > #  Задача. 
  >> * Написать программу, которая из имеющегося массива строк формирует новый массив из строк, длина которых меньше, либо равна 3 символам. Первоначальный массив можно ввести с клавиатуры, либо задать на старте выполнения алгоритма. При решении не рекомендуется пользоваться коллекциями, лучше обойтись исключительно массивами.
  >  -----------------
  > * Блок-схема алгоритма.
 >![текст схема](%D1%82%D0%B5%D0%BA%D1%81%D1%82%D0%BE%D0%B2%D0%B0%D1%8F%20%D1%81%D1%85%D0%B5%D0%BC%D0%B0.png)
   >  -----------------
   > ##  Описание алгоритма решения задачи.
     > * задаем исходный массив строк
     > * Определяем количество элементов,содержащих не более 3 (трёх) символов (так определяем размер итогового массива).
     > * создание итогового массива
         нужного размера
        (количество элементов с
        3-мя и менее символами, являются
        размером итогового массива)
    > * Проверяем в исходном массиве элемент содержит 3 и менее символов? 
    если да то добавляем элементы в итоговый массив
    > * печатеам итоговый массив
      >  -----------------
      > #  Код решения задачи.
>> * находится в папке KOD
>> * еще дополнительно сделал схему с кодом и циклами for:
>![код схемма](%D0%9A%D0%BE%D0%B4%20%D1%81%D1%85%D0%B5%D0%BC%D0%B0%20.png)
