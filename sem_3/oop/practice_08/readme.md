## Задание

>1. создать 2 аннатации для полей:
>   - @Ok
>   - @Ugly - с целочисл параметром k (k = <какое-то число> default)
>
>2. Создать класс Data, содержащий 5+ целочисл полей:
>   - 2 поля с аннотацией - @Ok
>   - 2 поля - @ugly
>   - 1 пле без аннотации
>
>3. Создать класс SaveData. Класс берет данные из класса data и пишет в файлик:
>   - если поле - @Ok -> записываем в файл как есть 
>   - если поле - @Ugly -> перед выводом заменяем его значение на случайное (k - из аннотации @Ugly; random (-k, k))
>   - если без аннотации -> выводим 'имя:значение' в консоль
>   - пример вывода в файл (json):\
     {\
        "a":1,\
        "b":2,\
        "c":-6,\
        "d":4\
      }\
