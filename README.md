# LR5-REST-API
Удаленное файловое хранилище, предоставляющее REST API по протоколу HTTP  

## HTTP-клиент: Postman  

## Сервер запустится на http://localhost:5137/  

![image](https://github.com/user-attachments/assets/14d7bd6f-2b61-4f54-9290-bdcdbd90ba7a)

### 1. Загрузка файла в корневую директорию   

![image](https://github.com/user-attachments/assets/b5014ddc-8943-4ec5-9706-89cf9b6bf860)


### 2. Проверка наличия файла 
![image](https://github.com/user-attachments/assets/595ec407-20b5-4a95-b1f2-de4d20a87e5b)





### 3. Создание файла во вложенной директории 
![image](https://github.com/user-attachments/assets/1cc700c1-c8b8-482d-862d-cfa5416c9dd2)

### 4. Проверка файла во вложенной директории 
![image](https://github.com/user-attachments/assets/943ab432-42cf-4f31-8562-3ff9bbaed8db)
### 5. Просмотр структуры директорий 

![image](https://github.com/user-attachments/assets/5df60e53-260a-429b-87f7-16bd9f358879)



### 6. Удаление файла 


![image](https://github.com/user-attachments/assets/f03a7d22-5af3-4a60-a020-5d20bb8bc8ab)




### 7. Проверка удаления файла 


![image](https://github.com/user-attachments/assets/ab22e26c-fc3e-4b0f-8afa-e090eac27dac)





### 8. Получение метаданных файла

![image](https://github.com/user-attachments/assets/b7f514e4-0046-400d-ab41-c4d0524a2a16)


### 9. Удаление пустой директории

![image](https://github.com/user-attachments/assets/e1be1e9a-79e5-4276-b94b-866ff35f4713)


### 10. Проверка удаления

![image](https://github.com/user-attachments/assets/6bcd6eac-8a3e-4988-9a19-dbf73db53975)
### 11. Просмотр содержимого конкретной директории


![image](https://github.com/user-attachments/assets/4a596cb3-e3f9-4c33-bc17-18843560240a)

## Примечания 📝

- Все пути в URL должны быть URL-encoded
- При создании файла во вложенной директории, директория создается автоматически
- При попытке удалить непустую директорию вернется ошибка `409 Conflict`
- При удалении папки Storage она создается при следующем запуске
 
