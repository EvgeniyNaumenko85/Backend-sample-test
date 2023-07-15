# REST API Для Создания Тестового образца серверной части (Backend sample test)


## <a href="https://github.com/EvgeniyNaumenko85/Backend-sample-test">Ссылка на проект в GitHub</a>

## В проекте разобранны следующие концепции:
### API позволяет пользователю: 
- зарегистрироваться
- войти в систему
- опубликовать текстовое сообщение
- посмотреть опубликованные ранее сообщения (с использованием пагинации)
- выборочно удалить сообщение

### Использованы следующие технологии и библиотеки:
- регистрация и аутентификация: JWT и middleware
- фреймворк Gin
- GORM
- подход Чистой Архитектуры в построении структуры приложения. Dependency injection
- работа в СУБД PostgreSQL. Генерация файлов миграций
- для ведения логгированя использована библиотека: https://github.com/natefinch/lumberjack
- для оформления документации использована библиотека: https://github.com/swaggo/swag
- "Graceful Shutdown"
- *запуск из Docker (under construction) 

