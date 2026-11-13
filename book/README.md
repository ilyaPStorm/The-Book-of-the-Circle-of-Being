# Книга Круга · The Book of the Circle of Being

Полный текст Книги Круга в двух версиях — русский канон и официальный английский перевод, — сверенных стих к стиху.
The full text of The Book of the Circle of Being in two versions — the Russian canon and the official English translation — aligned verse by verse.

**Проверка 2026-10-10:** структура и ID совпадают, но обнаружены смысловые расхождения английского перевода. Постиховое выравнивание не означает смысловую идентичность.

**Audit 2026-10-10:** structural alignment passes; semantic differences were found in the English translation. This edition is not certified as a semantically equivalent translation or a reviewed training target.

*Записал услышавший Книгу.* · *Recorded by the one who heard the Book.*

## Что здесь · What is here

| Папка · Folder | Содержание · Contents |
|---|---|
| [`ru/`](ru/) | Русский текст: [вся книга одним файлом](ru/book-ru.md), [главы](ru/chapters/), [`verses.jsonl`](ru/verses.jsonl) |
| [`en/`](en/) | Official English: [the whole book](en/book-en.md), [chapters](en/chapters/), [`verses.jsonl`](en/verses.jsonl) |
| [`bilingual/`](bilingual/) | Русский и английский рядом · side by side: [главы · chapters](bilingual/chapters/), [`verses.jsonl`](bilingual/verses.jsonl) |
| [`front-matter.json`](front-matter.json) | Эпиграф, названия глав, заключительная формула · epigraph, chapter titles, closing formula |
| [`manifest.json`](manifest.json) | Источники, заметки о сверке, контрольные суммы · sources, alignment notes, checksums |

12 глав · 12 chapters · 2127 стихов · 2127 verses.

| | Русский | English |
|---|---|---|
| 1 | Дух | Spirit |
| 2 | Мир | The World |
| 3 | Путь | The Path |
| 4 | Дверь | The Door |
| 5 | Пустота | The Void |
| 6 | Облики | The Forms of the Gods |
| 7 | Опора | The Foundation |
| 8 | Продолжение | Continuation |
| 9 | Сердце | The Heart |
| 10 | Различение | Discernment |
| 11 | Пробужденный | The Awakened |
| 12 | Приближение | Approaching |

## Нумерация · Numbering

Адрес стиха — `глава:стих` (например, `12:77`) по каноническому русскому изданию 2024 года. Английский текст размечен теми же адресами, поэтому `12:77` в обеих версиях — один и тот же стих.

A verse address is `chapter:verse` (for example `12:77`) following the canonical Russian edition of 2024. The English text uses the same addresses, so `12:77` is the same verse in both versions.

На сайте circlebook.info нумерация абзацев местами расходится с каноном; при сверке это исправлено. Пять стихов сопоставлены не один к одному (поле `alignment`):

On circlebook.info the paragraph numbering differs from the canon in a few places; the alignment corrects this. Five verses are not one-to-one (field `alignment`):

| Стих · Verse | Сверка · Alignment |
|---|---|
| 1:64, 1:65 | на сайте один абзац, в каноне два стиха · one site paragraph, two canonical verses (`split_from_merged`) |
| 6:74, 6:75 | на сайте один абзац, в каноне два стиха · one site paragraph, two canonical verses (`split_from_merged`) |
| 6:78 | на сайте два абзаца, в каноне один стих · two site paragraphs, one canonical verse (`joined_from_two`) |

## Формат данных · Data format

Каждая строка `verses.jsonl` — один стих · each line of `verses.jsonl` is one verse:

```json
{"id": "12:77", "chapter": 12, "verse": 77, "text": "…"}
```

`bilingual/verses.jsonl` содержит оба текста · contains both texts: `{"id", "chapter", "verse", "ru", "en", "alignment"}`.

## Где читать · Where to read

- Русский: [KnigaKruga.ru](https://knigakruga.ru)
- English: [circlebook.info](https://circlebook.info/en/)

## Источники и права · Sources and rights

- Русский текст: «Книга Круга», © Общество Всеобщего Круга, составитель, 2024 (ISBN 978-5-0064-9466-4).
- English: the official translation published by the Universum Circle Society at circlebook.info.

Права на тексты принадлежат Обществу Всеобщего Круга. · The texts are © the Universum Circle Society.
