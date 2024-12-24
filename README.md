# Решение тестовой задачи по распознаванию именованных сущностей с помощью LLM:

## Описание

  В работе рассмотрены этапы решения задачи распознавания именованных сущностей:
  1) Выгрузка размеченных данных;
  2) Составление промпта к LLM для NER;
  3) Внесение ответов LLM;
  4) Оценка ответов LLM;
  5) Анализ результатов и формирование выводов с целью улучшения результатов LLM в решении задач распознавания именованных сущностей.

## Структура

__Датасет:__ - [Balto-Slavic NLP](https://bsnlp.cs.helsinki.fi/bsnlp-2019/shared_task.html).

__notebooks:__ - содержит единтсвенный ноутбук с решением задачи поэтапно

__giga-output.csv:__ - csv файл с ответами gigachat и оценками

## Требования

- Код был написан на Python 3.13
- Зависимости из файла `requirements.txt`