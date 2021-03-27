# Отчёт о тестировании Precision
## Краткое описание
26/03/2021 - 26/03/2021 было проведено функциональное тестирование приложения **Precision**.    
 
На тестирование затрачено: 2 часа    
 
В результате тестирования выявлен дефект:    

* [Неверное число в ответе с 16ю знаками после запятой, при сложении двух десятичных чисел](https://github.com/Maksim-Shalaev/Precision/issues/1)  

## Описание процесса тестирования
В процессе тестирования использовались следующие артефакты:  
 
* [Руководство по установке IntelliJ IDEA](https://github.com/netology-code/javaqa-homeworks/blob/master/intro/idea.md)
* Исходный код
    
		public class Main { public static void main(String[] args) { double regularBonus = 0.3;
        double specialBonus = 0.6; double totalBonus = regularBonus + specialBonus; System.out.println(totalBonus);}} 

В качестве тестовых данных использовались данные:   

* Данные не менялись, согласно [условию задачи #2](https://github.com/netology-code/javaqa-homeworks/tree/master/programming) 
   
Тестирование производилось в следующем окружении: 

* Windows 7   
* Java 11.0.10  
* Intellij IDEA Community 2020.3