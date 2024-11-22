# Дополнительный проект из урока 6: Анализ данных генома

## Описание проекта

В этом проекте проводится анализ данных генома мухи, представленных в формате GFF. Проект включает выделение и анализ строковых данных в колонках, которые нечасто встречаются в традиционных аналитических задачах.

## Данные

GFF (General Feature Format) — это формат файла, используемый для представления аннотаций геномных данных. Каждая строка описывает геномный элемент, такой как ген или область кодирования. Поле `attributes` включает различные характеристики и параметры геномных элементов, среди которых и `Parent` (указывающий на родительский элемент).

### Основные колонки в файле GFF:
- **seqid**: Идентификатор последовательности (например, хромосома)
- **source**: Источник аннотации
- **type**: Тип элемента (ген, экзон, регион и т.д.)
- **start** и **end**: Начало и конец элемента в геноме
- **score**: Оценка (может быть пустым)
- **strand**: Направление (плюс или минус)
- **phase**: Фаза кодирования (может быть пустым)
- **attributes**: Дополнительные атрибуты, включая `Parent` и другие параметры

## Задачи

1. **Извлечение значения атрибута Parent**
   - Извлеките значение атрибута `Parent` из колонки `attributes`. Например, если запись имеет вид `Parent=x`, выделите `x`.

2. **Анализ частотности значений Parent**
   - Определите наиболее часто встречающееся значение атрибута `Parent`.

3. **Распределение типов элементов**
   - Постройте график распределения значений в столбце `type` и проанализируйте частотность различных типов геномных элементов.

## Выводы

Этот проект позволяет освоить анализ биоинформатических данных и навыки работы со строками в pandas. Выполнение задач поможет лучше понять структуру и особенности геномных данных, а также получить представление о наиболее распространенных элементах генома мухи.


# Additional Project from Lesson 6: Genome Data Analysis

## Project Description

This project involves analyzing genome data of a fly, presented in GFF format. The analysis includes extracting and interpreting string data from columns that are not commonly encountered in traditional analytics tasks.

## Data

GFF (General Feature Format) is a file format used to represent genome annotations. Each row describes a genomic feature such as a gene or coding region. The `attributes` field includes various properties and parameters of genomic elements, including `Parent` (indicating the parent element).

### Main Columns in the GFF File:
- **seqid**: Sequence identifier (e.g., chromosome)
- **source**: Annotation source
- **type**: Type of element (gene, exon, region, etc.)
- **start** and **end**: Start and end of the element in the genome
- **score**: Score (can be empty)
- **strand**: Direction (plus or minus)
- **phase**: Coding phase (can be empty)
- **attributes**: Additional attributes, including `Parent` and other parameters

## Tasks

1. **Extract the `Parent` Attribute**
   - Extract the value of the `Parent` attribute from the `attributes` column. For example, if the record reads `Parent=x`, extract `x`.

2. **Analyze the Frequency of `Parent` Values**
   - Determine the most frequently occurring value of the `Parent` attribute.

3. **Distribution of Element Types**
   - Create a chart showing the distribution of values in the `type` column and analyze the frequency of different genomic element types.

## Conclusions

This project provides experience in analyzing bioinformatics data and working with string manipulation in pandas. Completing these tasks will help in understanding the structure and features of genomic data and gaining insights into the most common genomic elements of a fly.
