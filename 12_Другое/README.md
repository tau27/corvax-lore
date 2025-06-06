# Папка 12_Другое

Эта папка служит для хранения материалов, которые **не вписываются** в другие, более специализированные категории. Для создания подробных описаний рекомендуется использовать шаблон `TEMPLATE.md`.

## Содержание информации

Здесь размещаются различные материалы, которые пока не имеют четкой классификации, включая:

- **Разрозненные заметки, концепты, временные черновики:** Предварительные записи, наброски идей, которые еще не оформлены в полноценные статьи.
- **Идеи, находящиеся в процессе обсуждения:** Материалы, которые находятся на стадии разработки и еще не определены в конкретную категорию.
- **Всё, что пока не имеет отдельного места:** Любые другие описания, концепции или заметки, которым пока не нашлось подходящего раздела.

Для описания каждого отдельного материала рекомендуется использовать файл `TEMPLATE.md`, скопировав его содержимое и заполнив соответствующие разделы.

## Рекомендации по структурированию информации

Использование строгой структуры категорий внутри Markdown файлов (с заголовками и подзаголовками, как показано в `TEMPLATE.md`) является лишь **рекомендацией** для обеспечения единообразия и удобства чтения.

## Обязательная структура хранения

Для лучшей организации информации **каждый отдельный материал**, концепт или заметка **должны** иметь **свою собственную папку**.

Внутри каждой папки **обязательно** должен лежать `.md`-файл с основным содержанием описания, а также файл `design_document.md`, описывающий концепцию данного материала. При необходимости хранения изображений, связанных с материалом, следует создать папку `images/` внутри папки материала. При росте количества файлов в папке "Другое" рекомендуется создавать дополнительные подпапки для тематической организации (например, `черновики/`, `unused_concepts/`). По мере развития лора и уточнения классификации, статьи из папки "Другое" рекомендуется **переносить** в более подходящие папки.

## Обязательное дополнение - design_document.md

Для каждого материала, размещенного в этой папке, **обязательно** создание файла `design_document.md` в корневой папке соответствующего материала. Этот документ служит для описания концепции и основных принципов данного материала, а также вариантов его возможного развития или интеграции в лор.

## 📁 Структура хранения материалов

```
[Название_материала]/
├── images/
│   ├── [изображение_1].png
│   └── [изображение_2].jpg
├── design_document.md
└── [Название_материала].md
```

- `[Название_материала]/` - корневая папка с информацией о конкретном материале, концепте или заметке.
- `images/` - подпапка для изображений, относящихся к данному материалу (необязательно).
- `design_document.md` - документ, описывающий концепцию и принципы, лежащие в основе данного материала (обязательно).
- `[Название_материала].md` - основной файл с подробным описанием материала, созданный на основе `TEMPLATE.md`.
