# Портофолио

## Оглавление
- [О себе](https://github.com/tolisso/portfolio/blob/main/README.md#%D0%BE-%D1%81%D0%B5%D0%B1%D0%B5)
- [Достижения](https://github.com/tolisso/portfolio/blob/main/README.md#%D0%B4%D0%BE%D1%81%D1%82%D0%B8%D0%B6%D0%B5%D0%BD%D0%B8%D1%8F)
- [Опыт работы](https://github.com/tolisso/portfolio/blob/main/README.md#%D0%BE%D0%BF%D1%8B%D1%82-%D1%80%D0%B0%D0%B1%D0%BE%D1%82%D1%8B)
- [Коллаборатор в базе данных Otterbrix](https://github.com/tolisso/portfolio/blob/main/README.md#1-%D0%BA%D0%BE%D0%BB%D0%BB%D0%B0%D0%B1%D0%BE%D1%80%D0%B0%D1%82%D0%BE%D1%80-%D0%B2-%D0%B1%D0%B0%D0%B7%D0%B5-%D0%B4%D0%B0%D0%BD%D0%BD%D1%8B%D1%85-otterbrix)
- [Pet Проект: Инструмент по построению дорожных систем](https://github.com/tolisso/portfolio/blob/main/README.md#2-%D0%B8%D0%BD%D1%81%D1%82%D1%80%D1%83%D0%BC%D0%B5%D0%BD%D1%82-%D0%BF%D0%BE-%D0%BF%D0%BE%D1%81%D1%82%D1%80%D0%BE%D0%B5%D0%BD%D0%B8%D1%8E-%D0%B4%D0%BE%D1%80%D0%BE%D0%B6%D0%BD%D1%8B%D1%85-%D1%81%D0%B8%D1%81%D1%82%D0%B5%D0%BC)
- [Pet Проект: ИИ машин без врезаний друг в друга](https://github.com/tolisso/portfolio/blob/main/README.md#3-%D0%B8%D0%B8-%D0%BC%D0%B0%D1%88%D0%B8%D0%BD-%D0%B1%D0%B5%D0%B7-%D0%B2%D1%80%D0%B5%D0%B7%D0%B0%D0%BD%D0%B8%D0%B9-%D0%B4%D1%80%D1%83%D0%B3-%D0%B2-%D0%B4%D1%80%D1%83%D0%B3%D0%B0)
- [Pet Проект: Простенький язык программирования](https://github.com/tolisso/portfolio/blob/main/README.md#4-%D0%BF%D1%80%D0%BE%D1%81%D1%82%D0%B5%D0%BD%D1%8C%D0%BA%D0%B8%D0%B9-%D1%8F%D0%B7%D1%8B%D0%BA-%D0%BF%D1%80%D0%BE%D0%B3%D1%80%D0%B0%D0%BC%D0%BC%D0%B8%D1%80%D0%BE%D0%B2%D0%B0%D0%BD%D0%B8%D1%8F)


## О себе

Малько Егор Александрович \
Возраст: 25 лет \
Город: Санкт-Петербург \
Гражданство: РФ \
Образование: ИТМО ФИТиП (бакалавриат и магистратура)

## Достижения

Олимпиады:
- Московская Олимпиада по Информатике - Победитель
- Заключительный этап Всероссийской Олимпиады по Информатике - Участник от сборной Москвы  

ЕГЭ:
- Информатика - 100 баллов
- Математика - 98 баллов
- Русский Язык - 87 баллов

Cертификаты:
- *Oracle Certified Professional: Java SE 11 Developer*

## Опыт работы
### Диасофт
2 года \
Java Junior

Разрабатывали микросервисы для работы самописной JIRA использующейся внутри компании. Делал реализацию бизнес логики по учету задач, оценке команд по метрикам.

Технологии: *Spring Boot, Spring Data, Spring Web, Spring Security, Spring Core, Spring Actuator, PostgreSQL, Java 8, Kafka, Mockito, Docker, Jenkins, Kubernetes*

### Сбер

2 года \
Kotlin Middle

Разрабатывали высоконагруженную мастер-систему для СберДевайсов. Наши сервисы обеспечивали контроль всей информации и общей бизнес логики по девайсам. В частности к чему я имел отношение: вторизация пользователей и девайсов, backend часть передачи информации на устройства через WebSocket-ы, backend админ панели для тестирования устройстройств и устранения бизнес дефектов в production.

Технологии: *Kotlin, Ktor, Kodein, JOOQ, Selenium, Mockito, Kafka, PostgreSQL, Kibana, Grapghana, Docker, Jenkins, Kubernetes, Red Hat OpenShift*

## Проекты

Все проекты далее делались с использованием ИИ (Claude, Cursor)

### 1. Коллаборатор в базе данных Otterbrix

- [[PR]](https://github.com/otterbrix/otterbrix/pull/468) Реализация таблиц с динамической схемой
- [[PR]](https://github.com/otterbrix/otterbrix/pull/477) Реализация оптимизации по чтения только тех колонок таблиц которые используются в запросе
- [[PR]](https://github.com/otterbrix/otterbrix/pull/483) Изменение пайплайна исполнения запросов - теперь между операторами данные передаются частями котлорые можно распараллелить
- [[PR]](https://github.com/otterbrix/otterbrix/pull/488) Оптимизация оператора Distinct
- [[PR]](https://github.com/otterbrix/otterbrix/pull/489) Реализация бенчмарка на производительность JSONBench
- [[PR]](https://github.com/otterbrix/otterbrix/pull/497) Реализация HashJoin
- [[PR]](https://github.com/otterbrix/otterbrix/pull/499) Операторы JSONB для работы с динамическими таблицами

### 2. Инструмент по построению дорожных систем

Простенький инструмент для построения дорог (как в SimCity). Формулы и систему для корректного построения придумывал сам.

https://github.com/user-attachments/assets/18e90bdf-53b9-49a6-b7e6-a84e6518cb99

[Ссылка на репо](https://github.com/tolisso/car2)

### 3. ИИ машин без врезаний друг в друга

Математическая система, в которой машины ездят по дорогам и не врезаются друг в друга. При этом машины не знают как поведут себя другие участники дорожного движения и сами оценивают риски. 

Систему придумал сам, позже оказалось, что она была изобретена еще в нулевых.

https://github.com/user-attachments/assets/be0d2cdf-c3ab-4d9b-8e2e-efb32a4522d0

[Ссылка на репо](https://github.com/tolisso/car4)

### 4. Простенький язык программирования

Простенький язык программирования. Компилятор на языке Kotlin с использованием Antlr и LLVM.

Пример кода:

```
// Переменные
a = 10
b = 20
c = a + b
print(c)  // 30

// Составное присваивание
c += 5
print(c)  // 35

// Арифметика
x = 100
y = 25
result = x / y + 10
print(result)  // 14
```

[Ссылка на репо](https://github.com/tolisso/easy-lang)
