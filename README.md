# Компьютерное зрение
```diff
- Код был написан на платформе Google Colab
```
## Тест - проверка остаточных знаний (test)
1. Загрузить изображение
2. Построить гистограмму по каждому из каналов (RGB)

## Лабораторная 1. Яркостные преобразования (lab1)
1. Загрузка изображения
2. Преобразование к полутоновому изображению
3. Цветовая коррекция изображений
  1. Коррекция с опорным цветом
  2. Серый мир
  3. По виду функции преобразования
4. Яркостная коррекция в интерактивном режиме по виду функции преобразования (необязательное дополнительное задание)
  1. График функции кусочно линейный
  2. График функции интерполируется сплайном
5. Коррекция на основе гистограммы
  1. Нормализация гистограммы
  2. Эквализация гистограммы

## Лабораторная 2. Бинаризация и квантование (lab2)
1. Загрузка изображения и преобразование цветного к полутоновому
2. Квантование по яркости (с ручным заданием количества уровней)
3. Бинаризация
  1. Бинаризация методом Оцу глобальная
  2. Бинаризация методом Оцу локальная (с предварительным разбиением на фрагменты - по каждому своя бинаризация)
  3. Бинаризация методом Оцу иерархическая (выполняется с иерархическим разбиением каждой уже полученной  области, пока возможно разбивать). Квантование с использованием найденных порогов

## Лабораторная работа 3. Морфологические преобразования (lab3)

Морфологические преобразования
Следует реализовать выделение проблемных зубьев у шестеренки. Пример разобран на лекции.
Описание есть у Стокмана.
Использовать только морфологические операции для бинарных изображений.
Можно использовать для этого функции OpenCV, например:
Erode -- размывание(операция сужения) 
Dilate -- растягивание(операция расширения)
и др.

## Лабораторная 4. Пространственная фильтрация (lab4)

Выполнить улучшение изображения по описанию (Гонсалес п.3.8 или 3.7 (зависит от года издания), кратко в презентации) (lab4)

## Лабораторная 5. Частотная фильтрация (lab5)

Частотная фильтрация.
Для частотной фильтрации использовать БПФ (средствами OpenCV)
Показать пошаговое применение частотных сглаживающих и повышающих резкость фильтров:
Показать в сравнении идеальный фильтр, Батерворта и гауссиан

Что нужно показывать!!!
- Исходное изображение.
- Спектр изображения
- Частотный фильтр для сглаживания
- Результат наложения в виде спектра и в виде изображения
- Частотный фильтр для повышения резкости
- Результат наложения в виде спектра и в виде изображения

## Лабораторная 6. Сегментация методами водораздела (lab6)

Выполнить сегментацию как на образце, применяя методы водораздела.
Исходное изображение слева вверху. Получить все четыре изображения.
Подробное описание: Гонсалес р.10.5

## Проект 1. (Project)

Групповой проект.
Обязательно использовать гитхаб для выполнения проектов 
