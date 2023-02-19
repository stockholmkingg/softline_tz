# Тестовое задание на позицию "Ведущий специалист 
(Разработчик No-Code)".

---

## Задание №1.
### [Ссылка на regex101.](https://regex101.com/r/edqfO3/1)
### Само регулярное выражение:
```
^[а-яёА-Яa-zA-Z0-9 ]+$
^[0-9]+$
^[a-zA-Z0-9]+$
^[а-яёЁА-Я0-9 ]+$
```

---

## Задание №2
### Скрин запроса:
![POST-запрос](images%2Fpost.png)
### Query Params (API-key замазан):
![query params.png](images%2Fquery%20params.png)
### Результат запроса (scan): 
![json_scan.png](images%2Fjson_scan.png)
### Результат запроса (result): 
![json_result.png](images%2Fjson_result.png)
#### [Ссылка на JSON с полным результатом сканирования.](https://github.com/stockholmkingg/softline_tz/blob/main/files/scan_result.json)
### Authorization (API-key замазан):
![authorization.png](images%2Fauthorization.png)
### Headers:
![headers.png](images%2Fheaders.png)
### Body:
![body.png](images%2Fbody.png)

### Запрос работает в 2 этапа:
1. Сканирование <code>URL</code>, введённого в переменную <code>resource</code>. (Первое нажатие кнопки <code>Send</code>)
2. Получение результата сканирования <code>URL</code>. (Второе нажатие кнопки <code>Send</code>)
#### Если введённый <code>URL</code> уже был просканирован VirusTotal - запрос вернёт результат сканирования.

---

## Задание №3.
![diagram.png](images%2Fdiagram.png)
![diagram (1).png](images%2Fdiagram%20%281%29.png)
![diagram (2).png](images%2Fdiagram%20%282%29.png)
![diagram (3).png](images%2Fdiagram%20%283%29.png)