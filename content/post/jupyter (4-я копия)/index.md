---
title: Текстовый редактор Vi
subtitle: Давайте узнаем больше о текстовых редакторах
summary: Давайте узнаем больше о текстовых реакторах
authors:
  - admin
tags: []
categories: []
projects: []
date: '2023-04-19T00:00:00Z'
lastMod: '2023-04-19T00:00:00Z'
image:
  caption: ''
  focal_point: ''
---

```
```

1. Команды позиционирования
– 0 (ноль) — переход в начало строки;
– $ — переход в конец строки;
– G — переход в конец файла;
– 𝑛 G — переход на строку с номером 𝑛.
2. Команды перемещения по файлу
– Ctrl-d — перейти на пол-экрана вперёд;
– Ctrl-u — перейти на пол-экрана назад;
– Ctrl-f — перейти на страницу вперёд;
– Ctrl-b — перейти на страницу назад.
3. Команды перемещения по словам1
– W или w — перейти на слово вперёд;
– 𝑛 W или 𝑛 w — перейти на 𝑛 слов вперёд;
– b или B — перейти на слово назад;
– 𝑛 b или 𝑛 B — перейти на 𝑛 слов назад.
4. Вставка текста
– а — вставить текст после курсора;
– А — вставить текст в конец строки;
– i — вставить текст перед курсором;
– 𝑛 i — вставить текст 𝑛 раз;
– I — вставить текст в начало строки.
5.  Вставка строки
– о — вставить строку под курсором;
– О — вставить строку над курсором.
6. Удаление текста
– x — удалить один символ в буфер;
– d w — удалить одно слово в буфер;
– d $ — удалить в буфер текст от курсора до конца строки;
– d 0 — удалить в буфер текст от начала строки до позиции курсора;
– d d — удалить в буфер одну строку;
– 𝑛 d d — удалить в буфер 𝑛 строк
7. Отмена и повтор произведённых изменений
– u — отменить последнее изменение;
– . — повторить последнее изменение.
8.  Копирование текста в буфер
– Y — скопировать строку в буфер;
– 𝑛 Y — скопировать 𝑛 строк в буфер;
– y w — скопировать слово в буфер.
9.  Вставка текста из буфера
– p — вставить текст из буфера после курсора;
– P — вставить текст из буфера перед курсором.
10. Замена текста
– c w — заменить слово;
– 𝑛 c w — заменить 𝑛 слов;
– c $ — заменить текст от курсора до конца строки;
– r — заменить слово;
– R — заменить текст.

1. Position commands
– 0 (zero) — jump to the beginning of the line;
– $ — jump to the end of the line;
– G — go to the end of the file;
– 𝑛 G — jump to the line with the number 𝑛.
2. Commands for moving through the file
- Ctrl-d - move forward half a screen;
– Ctrl-u — go half a screen back;
- Ctrl-f - go to the page forward;
– Ctrl-b — go back a page.
3. Commands for moving by words1
– W or w — move one word forward;
– 𝑛 W or 𝑛 w — move forward 𝑛 words;
- b or B - go back a word;
– 𝑛 b or 𝑛 B — go back 𝑛 words.
4. Insert text
– a — insert text after the cursor;
– A — insert text at the end of the line;
– i — insert text before the cursor;
– 𝑛 i — insert text 𝑛 times;
- I - insert text at the beginning of the line.
5. Insert a row
– o — insert a line under the cursor;
– О — insert a line above the cursor.
6. Removing text
– x — delete one character to the buffer;
– d w — delete one word in the buffer;
– d $ — delete text from the cursor to the end of the line into the buffer;
– d 0 — delete text from the beginning of the line to the cursor position into the buffer;
– d d — delete one line into the buffer;
– 𝑛 d d — delete 𝑛 lines into the buffer
7. Undo and redo changes made
– u — undo the last change;
– . - redo last change.
8. Copy text to clipboard
– Y — copy the string to the buffer;
– 𝑛 Y — copy 𝑛 lines to buffer;
– y w — copy the word to the clipboard.
9. Paste text from clipboard
- p - paste text from the buffer after the cursor;
- P - paste text from the buffer before the cursor.
10. Text replacement
– c w — replace a word;
– 𝑛 c w — replace 𝑛 words;
- c $ - replace the text from the cursor to the end of the line;
- r - replace the word;
- R - replace text.

![png](./index_1_0.png)

```

```







