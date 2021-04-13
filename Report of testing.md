# Отчёт о тестировании программы Precision

## Краткое описание

13 апреля 2021 г. было проведено функциональное тестирование программы Precision.

На тестирование затрачено: 2 ч

В результате тестирования выявлены следующие дефекты:
* [Precision] Неверная сумма итогового бонуса для новых клиентов 
https://github.com/EkaterinaSkobeleva/12HomeworkJavaEx2/issues/1


## Описание процесса тестирования

В процессе тестирования использовались следующие артефакты:
* код из файла Main.java репозитория https://github.com/EkaterinaSkobeleva/12HomeworkJavaEx2, запущенный в среде IDEA


В качестве тестовых данных использовались данные из задачи №2 https://github.com/netology-code/javaqa-homeworks/tree/master/programming

Входные данные:

	* double regularBonus = 0.3;
    * double specialBonus = 0.6;
    * double totalBonus = regularBonus + specialBonus;
	
Ожидаемый результат: переменная totalBonus=0.9


Тестирование производилось в следующем окружении:
* OS Microsoft Windows 10 Домашняя, v. 19042.867, x64
* Окружение Java OpenJDK11U-jdk_x64_windows_hotspot_11.0.10_9
* IntelliJ IDEA Community 2020.3.3
