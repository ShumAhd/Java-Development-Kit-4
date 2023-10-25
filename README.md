# Java Development Kit (семинары)
## Урок 4. Коллекции

# Справочник сотрудников

Справочник сотрудников представлен в виде Java-приложения, состоящего из нескольких классов, позволяющих добавлять сотрудников, искать их по различным атрибутам и выводить информацию о них.

## Использование

1. Добавление нового сотрудника:
   ```java
   EmployeeDirectory directory = new EmployeeDirectory();
   directory.addEmployee(1, "+1234567890", "Иванов", 5);

2. Поиск сотрудников по стажу:
   ```java
   List<EmployeeDirectory.Employee> employeesWithExperience5 = directory.findEmployeesByExperience(5);

3. Поиск номера телефона сотрудника по имени:
   ```java
   String phoneNumber = directory.findPhoneNumberByName("Петров");

4. Поиск сотрудника по табельному номеру:
   ```java
   EmployeeDirectory.Employee employee = directory.findEmployeeByEmployeeId(2);

## Вывод в консоли
```
Сотрудники со стажем 5 лет:
Иванов
Сидоров
Номер телефона Петрова: +9876543210
Сотрудник с табельным номером 2 найден: Петров
```
