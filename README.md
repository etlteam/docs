# ETL
Если коротко описать наш проект, то это простой и удобный для пользователя web-интерфейс для создания, запуска и мониторинга ETL-пайплайнов.

Основная функциональность:
- создание и редактирование пайплайнов обработки данных
- API для взаимодействия с интеграционными платформами (Zapier, n8n, make и подобные)

## Требования
### Функциональные
- при создании комнаты сервис генерирует уникальную короткую ссылку; если комната приватная, то
и ключ доступа
- при создании комнаты видео по ссылке скачивается на наш CDN
- должна быть возможность запланировать встречу
- должна быть возможность подключиться к комнате как минимум 5 людям
- к приватной комнате нельзя подключиться не зная пароль
- каждый участник комнаты может управлять общим поток без ограничения (плей/пауза/перемотка/звук)
- каждый участник комнаты может управлять своей трансляцией (включать/отключать звук/видео)
- каждый участник может писать сообщения в чат
- каждый подключающийся в процессе должен иметь доступ к истории чата с самого начала
- вся информация о комнате (включая видео и чат) должна быть доступна минимум три года и максимум
через 3 часа после завершения трансляции
### Нефункциональные
- не должно быть единой точки отказа
### Дополнительные
- возможность собирать аналитику
- автоматическое масштабирование сервиса в зависимости от нагрузки (k8s, облачные решения)
## Оценка ограничений и пропускной способности
Предположим, что у нас одномоментно активно 100 комнат, в каждом комнате в среднем 30 человек и
продолжительность вещания 2 часа.
### Трафик
### Хранилище
### Память
### Пропускная способность
### CPU
## Проектирование API
## Проектирование уровня хранения данных, схема, партицирование
## Схема

## Базовый алгоритм и архитектура

## Масштабирование
## Кэширование
## Диаграмма вариантов использования
![](use_case_diagram.svg)
## Диаграмма классов
## Диаграмма активностей
## Диаграмма последовательности

## Страницы фронтенда
- Регистрация, вход, выход
- Главная страница с активными публичными комнатами
- страница создания комнаты
- Комната с трансляцией
- 404, 403, 500

## Дополнительная информация
### Альтернативые реализации
### Библиотеки
### Конференции
### Документация

