## Цифровой прорыв. Международный хакатон 2024 (победитель - 1 место)
### Контроль и управление изменениями в тендерных закупках. Компания "Атом"
##### Организатор: Цифровой прорыв 2024
https://hacks-ai.ru/events/1077382
##### Кейсодержатель: Компания "Атом"

## Описание кейса
Мы создали решение для контроля и управления изменениями в тендерных закупках, позволяющее анализировать и сопоставлять требования с использованием локальных моделей LLM. Данное решение включает продвинутые методы обработки текста с применением промптинга, обеспечивая высокую точность в выявлении соответствия между требованиями и спецификациями.

## Преимущества решения

- Использование моделей на CPU и GPU, что позволяет значительно ускорить обработку данных.
- Сокращение времени обработки одной пары документов с 1 минуты на CPU до 4,5 секунд на GPU.

***
### Презентация проекта
[Итоговая презентация решения на защите](docs/Skripka Международный ЦП 2024.pptx)


### Структура репозитария:
```
.
├── docs
│   ├── Описание решения.docx                   # Описание итогового решения
│   ├── Результаты  экспериментов.xlsx          # Результаты  экспериментов
│   ├── Skripka Международный ЦП 2024.pptx      # Презентация по решению на защите проекта
│   └── Структура документов.xlsx               # Разбор структуры анализируемых документов
├── SplitTextBySentence_1_4.ipynb               # Разбитие документов на разделы и детекция отедльно по разделам с последующей агрегацией
├── FULL_LAUNCH_v4.ipynb                        # Модуль расчета на GPU основе модели 01-ai/Yi-Coder-9B-Chat
├── requirements.txt                            # Перечень зависимостей
├── Final_submit.xlsx                           # финальный сабмит
└── README.md                                   # README   

```
## Зависимости
В файле requirements.txt перечислены все необходимые зависимости они будут установлены с помощью команды:  
```pip install -r requirements.txt```

## Документация 
Документация  расположена в папке ```docs```
[Документация](docs)

## Дополнительная информация
Подробное описание решения доступно по [ссылке](https://docs.google.com/document/d/14I6Dg6L9visXgy657yeqg7ntPKrdW7B3zrYLNjTVPxY/edit?tab=t.0).


