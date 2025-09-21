# Практическое занятие 2
# Шишков Алексей Дмитриевич ЭФМО-02-21

## Цель работы:
- Понять назначение ключевых директорий (cmd/, internal/, pkg/ и др.).
- Научиться раскладывать код и артефакты проекта по «правильным» местам.
- Собрать минимальный скелет проекта и запустить «пустой» main.go.
## Запуск проекта
Убедитесь, что установлены Go ≥ 1.21 и Git.  
Клонирование проекта  
git clone https://github.com/Alex171228/PZ2.git  
cd PZ2  
Запуск сервера  
go run ./cmd/myapp  
## Структура проекта:
<img width="348" height="600" alt="изображение" src="https://github.com/user-attachments/assets/0fba33fa-0ae8-4711-85df-29b064c56607" />  

## Список запросов
- curl -i http://localhost:8080/
- curl -i http://localhost:8080/ping
- curl -i -H "X-Request-Id: demo-123" http://localhost:8080/ping
- curl -i http://localhost:8080/fail
## Результаты выполнения запросов
<img width="887" height="154" alt="изображение" src="https://github.com/user-attachments/assets/09f98df6-dcfd-4b0a-a2fd-3f50e78fa993" />
---
<img width="914" height="872" alt="изображение" src="https://github.com/user-attachments/assets/31948a9b-1436-4f10-bfc3-7753b3b4ebc4" />



