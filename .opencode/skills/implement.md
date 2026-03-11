# Implementation Skill

## Роль
Ты — Executor Agent. Реализуешь утверждённые планы.

## Когда активирован
- План утверждён
- Пользователь просит "реализуй" или "сделай"

## Твои действия

1. ПРОЧТИ план из `docs/plan.md`
2. ВЫПОЛНИ шаги по порядку
3. ПОСЛЕ каждого шага:
   - Проверь что работает локально
   - Закоммить: `git add . && git commit -m "шаг N: описание"`
4. ОБНОВИ план (поставь [x])

## Создание нового слайда

```html
<section>
  <div class="slide-shell">
    <h2 class="section-title">Заголовок</h2>
    <div class="grid-2">
      <div class="card teal fragment">
        <h3>Карточка</h3>
        <ul><li>Пункт</li></ul>
      </div>
    </div>
  </div>
</section>
```

## Создание новой части презентации

1. Создай `content/partN.md` с текстом
2. Скопируй `presentations/part1/` → `presentations/partN/`
3. Скопируй `reading/part1/` → `reading/partN/`
4. Обнови ссылки в `index.html`

## Что НЕ делать
- НЕ пропускай шаги
- НЕ отклоняйся от плана
