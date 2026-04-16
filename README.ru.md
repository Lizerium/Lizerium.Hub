<h1 align="center">
  <img src="https://raw.githubusercontent.com/Lizerium/.github/main/media/logo.png" width="32" style="vertical-align: middle;" /> 
  Lizerium Hub 
</h1>

<p align="center">
  Навигационная точка по экосистеме Lizerium
</p>

<div align="center" style="margin: 20px 0; padding: 10px; background: #1c1917; border-radius: 10px;">
  <strong>🌐 Язык: </strong>
  
  <span style="color: #F5F752; margin: 0 10px;">
    ✅ 🇷🇺 Русский (текущий)
  </span>
  | 
  <a href="./README.md" style="color: #0891b2; margin: 0 10px;">
    🇺🇸 English
  </a>
</div>

---

> [!NOTE]
> Этот репозиторий — часть экосистемы **Lizerium**:
>
> - https://github.com/Lizerium

---

## Что это

`Lizerium.Hub` — это точка входа в экосистему.

Здесь нет реализации.  
Он нужен, чтобы быстро понять:

- какие есть направления
- как они разделены
- куда идти дальше

---

## Как этим пользоваться

> [!TIP]
> Если ты здесь впервые:
>
> 1. Выбери направление ниже
> 2. Перейди в соответствующий `*.Structs` репозиторий
> 3. Оттуда — в конкретные проекты

---

## Основные направления

### Game

Игровые форматы, ресурсы и структура данных Freelancer

→ https://github.com/Lizerium/Lizerium.Game.Structs

---

### Unity

Runtime-эксперименты и игровая логика на Unity

→ https://github.com/Lizerium/Lizerium.Unity.Structs

---

### Software

Серверы, backend и инфраструктура

→ https://github.com/Lizerium/Lizerium.Software.Structs

---

### Tools

Редакторы, парсеры и вспомогательные утилиты

→ https://github.com/Lizerium/Lizerium.Tools.Structs

---

### Frameworks

Валидация, тестирование и контроль целостности

→ https://github.com/Lizerium/Lizerium.Frameworks.Structs

---

## Как устроено

```

Lizerium
├── направление (Game / Unity / Software / ...)
│   └── *.Structs (карта слоя)
│       └── конкретные проекты

```

---

## Зачем это нужно

> [!IMPORTANT]
> Когда проектов становится много, без структуры всё превращается в хаос.
>
> Hub — это способ:
>
> - держать навигацию
> - разделять ответственность между частями системы
> - быстро находить нужные компоненты

---

## Важно

> [!TIP]
> Если ты ищешь конкретный инструмент или код — тебе не сюда.  
> Hub — это только карта.
