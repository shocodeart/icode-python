# Day 9

1. Создайте класс Person 
- с атрибутами имя, фамилия, возраст
- в классе должен быть init позволяющий менять указанные атрибуты
- реализуйте методы для человекочитаемости
- добавьте метод greeting, возвращающий строку Привет, я ТУТ_ИМЯ, мне ТУТ_ВОЗРАСТ
- добавьте метод is_adult возвращаюший True/False исходя из совершеннолетия
- создайте 3 объекта из этого класса, добавьте их в список и выведите список в консоль
- добавьте метод to_dict возвращающий словарь 
    
        {
            "name": ТУТ_ИМЯ,
            "surname": ТУТ_ФАМИЛИЯ,
            "age": ТУТ_ВОЗРАСТ
        }

- создайте 3 объекта из этого класса, добавьте в список результаты выполнения их метода to_dict и выведите список в консоль

        Пример результата для 1 объекта

        [
            {
                "name": ТУТ_ИМЯ,
                "surname": ТУТ_ФАМИЛИЯ,
                "age": ТУТ_ВОЗРАСТ
            }
        ]

   > IMPORTANT<br><br>
   ТУТ_ИМЯ, ТУТ_ВОЗРАСТ, ТУТ_ФАМИЛИЯ должны быть заменены на значения из атрибутов объекта
    

2. Создайте класс Phone
    - c атрибутами brand, display, color
    - в классе должен быть init позволяющий менять указанные атрибуты
    - реализуйте методы для человекочитаемости
    - создайте 3 объекта из этого класса и добавьте их в список

3. 
- создайте функцию list_to_dict(phones) принимающий предыдущий список из объектов Phone и возвращающий словарь вида:  

        {
            brand: {
                display
                color
            }
        }

 - выведите результат выполнения в консоль

    Пример вывода для списка из 2 объектов:

        {
            "xiaomi": {
                "display": 5,
                "color": "black",
            },
            "samsung": {
                "display": 6,
                "color": "black",
            },
        }