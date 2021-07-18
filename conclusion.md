# Отчёт о тестировании Money Transfer

## В ходе тестирования было проверено приложение Money Transfer на пополнение счета

18.07.2021 - 18.07.2021  было проведено тестирование Money Transfer

На тестирование затрачено: 3 часа

В результате тестирования выявлены следующие дефекты:

![Неверный расчет суммы при пополнении счета](https://github.com/ElenaTyutina/Money-Transfer/issues/1)

### Описание процесса тестирования

Было создано базовое приложение на основе кода 
```
public class Main {
    public static void main(String[] args) {
        int price = 2_000_000_000;
        int count = 500_000_000;
        int total = price * count;
        System.out.println(total);
    }
}
```

### Производился запуск программы с вводными данными в коде с помощью Run ,либо сочетание клавиш Shift + ctrl + f10

В качестве тестовых данных использовались ![ данные](https://github.com/netology-code/javaqa-homeworks/tree/master/programming#%D0%B7%D0%B0%D0%B4%D0%B0%D1%87%D0%B0-1---money-transfer)

Тестирование производилось в следующем окружении:

* Linux x64 ОС
* IntelliJ IDEA
* Java 11.0.11 2021-04-20





