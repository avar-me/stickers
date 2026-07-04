# Хӏарпик — базовый референс персонажа

Используется как неизменная часть каждого промпта, чтобы персонаж не "плыл" между стикерами.

## Имя
Хӏарпик (от "хӏарп" — буква)

## Мудборд (v0, до утверждения стиля)
`harpik-moodboard-v0.png` — исходный концепт-лист, с которого стартовала разработка
персонажа (имя, характер, палитра, состав набора). Финальный визуальный стиль (см. ниже)
разошёлся с этим мудбордом в деталях (перчатки/кроссовки/румянец добавились в процессе
генерации) — актуальный референс всегда `../png/final/01_barkala.png`, а не этот файл.

## Утверждённый стиль (v1, зафиксировано 2026-07-04)

Референс: `../png/final/01_barkala.png` (первый утверждённый стикер).

Стиль — глянцевый semi-3D sticker (не плоский flat-vector, как планировалось изначально
в первой версии ТЗ; после теста генерации решили принять этот вид как канон, т.к. он
выглядит мило и узнаваемо). Характеристики по референсу:

- Мягкие блики/glossy-хайлайты на обложке и страницах (не плоская заливка).
- Лёгкая мягкая тень под персонажем и лёгкий объём (soft shading), но БЕЗ сложных
  многослойных теней и БЕЗ реализма.
- Толстая белая sticker-обводка по всему силуэту + тёмно-синий контур персонажа.
- Румянец (розовые щёки) на страницах — стабильный элемент.
- Обложка книги ярко-синяя (#295BA7), страницы тёплый кремовый/бежевый (не белые).
- Глаза крупные, тёмно-синие, с маленьким белым бликом.
- Красная закладка/ленточка торчит из книги сбоку — стабильный мелкий элемент.
- Ноги — синие мультяшные кроссовки со шнурками (не просто "лапки").
- Руки — белые мультяшные перчатки.
- Подпись — тёмно-синий жирный текст под персонажем, на самом стикере (не отдельным слоем).

## Описание персонажа (base character sheet)

A cute mascot character: a large open book that is alive, standing upright like a small
biped creature. The book's left page shows the bold letters "АВ" and the right page shows
the bold letters "РУ", printed in a rounded bold sans-serif font. The book cover is bright
deep blue (#295BA7) with soft glossy highlights, the pages are warm cream/beige, and all
outlines are dark navy blue with a thick white sticker border around the whole character.
The character has big expressive dark blue round eyes with a small white highlight dot,
placed on the pages, with very emotive thick eyebrows that carry most of the emotion, and
soft pink blush circles on the pages/cheeks. The mouth is minimal and simple. It has two
white cartoon-glove hands on short flexible arms, blue cartoon sneakers with laces as feet,
and a small red bookmark ribbon sticking out of the book. Semi-3D glossy sticker illustration
style (soft highlights, gentle shading, soft drop shadow) — NOT flat, NOT fully realistic.
Telegram sticker style, bold clean shapes, no fine details, very readable at 100px size.
Transparent background (real alpha transparency, not a checkerboard image). Consistent
proportions, consistent eye/hand/shoe/book size across all images. Color palette limited to
6 core colors: #295BA7 (deep blue cover), #FFF4E0/cream (pages), #1E2A38 (dark navy outline),
white (gloves + border), #E8544E (red bookmark), pink (blush) — accent colors used only in
small details.

## Технические параметры экспорта
- Исходный размер: 2048×2048 (или нативный размер генератора)
- Экспорт: 512×512 PNG
- Прозрачный фон (реальный alpha-канал — проверять программно, не на глаз, т.к. превью
  инструментов может рисовать серую виньетку поверх прозрачности)
- Одна и та же поза "нейтральный анфас" как базовая, эмоции передаются бровями/ртом/руками

## Как использовать
Каждый промпт в `../prompts/` начинается с этого базового описания персонажа
(см. `../prompts/_base.md`), к которому добавляется конкретная эмоция, поза,
жест рук/ног, дополнительный элемент (если есть) и текстовая подпись стикера.
