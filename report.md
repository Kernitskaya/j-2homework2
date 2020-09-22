# Отчёт о тестировании Money Transfer

## Краткое описание

22.09 - 22.09 было проведено функциональное тестирование приложения Money Transfer.

На тестирование затрачено: 0 часов 11 минут

В результате тестирования выявлены следующие дефекты:
* Неправильно суммируются вещественные числа в приложении Precision (https://github.com/Kernitskaya/j-2homework2/issues/1)


## Описание процесса тестирования

В процессе тестирования использовались следующие артефакты*:
* Приложение Precision https://github.com/Kernitskaya/j-2homework2/blob/master/Precision/src/Main.java


В качестве тестовых данных использовались входные данные:
```
public class Main {
  public static void main(String[] args) {
    double regularBonus = 0.3;
    double specialBonus = 0.6;
    double totalBonus = regularBonus + specialBonus;
    System.out.println(totalBonus);
  }
}
```

Тестирование производилось в следующем окружении:
* Windows 10 - 64
* Openjdk version "11.0.8"