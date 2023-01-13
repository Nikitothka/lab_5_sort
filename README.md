# Лаборатоная работа 5
## Цель работы
Разработать и реализовать алгоритм внешней сортировки. Данные хранятся на сервере в массиве, ервер предоставляет доступ к отдельным элементам. Клиент поочередно запрашивая отдельные ячейки сортирует массив.
## Ход работы
- Разработаем пользовательский интерфейс и опишем пользовательские сценарии работы

![](https://github.com/AlDmitrieva/lab_5_sort/blob/main/5.png)

Первоначально пользователь попадает на главную форму (index.php). Затем он должен ввести несколько цифр в соответствующее окно ввода. Чтобы отсортировать введенные данные, ондолжен нажать на соответствующую кнопку и записанные ранее числа отсортируются.

- Опишем хореографию

![](https://github.com/AlDmitrieva/lab_5_sort/blob/main/%D0%A5%D0%BE%D1%80%D0%B5%D0%BE%D0%B3%D1%80%D0%B0%D1%84%D0%B8%D1%8F%20(5).png)

- Опишем структуру базы данных

| Название | Тип данных | Длина | Описание                                          |
|----------|------------|-------|---------------------------------------------------|
| ID       | int        |       | Ключевое поле                                     |
| NUM      | int        | 100   | Вводимые числа                                    |

- Опишем алгоритмы 

1. Добавление числа 
 
 ![](https://github.com/AlDmitrieva/lab_5_sort/blob/main/%D0%94%D0%BE%D0%B1%D0%B0%D0%B2%D0%BB%D0%B5%D0%BD%D0%B8%D0%B5%20%D1%87%D0%B8%D1%81%D0%BB%D0%B0.png)
  
  2. Сортировка
  
  ![](https://github.com/AlDmitrieva/lab_5_sort/blob/main/%D0%A1%D0%BE%D1%80%D1%82%D0%B8%D1%80%D0%BE%D0%B2%D0%BA%D0%B0.png)

## Вывод
Разработали и реализовали алгоритм внешней сортировки.
