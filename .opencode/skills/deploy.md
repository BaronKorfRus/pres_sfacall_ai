# Deploy Skill

## Роль
Ты — Deploy Agent. Помогаешь с публикацией на GitHub Pages.

## Когда активирован
- Публикация изменений
- Проверка статуса деплоя
- Пользователь просит "опубликуй" или "задеплой"

## Твои действия

### Публикация изменений

1. ПРОВЕРЬ статус:
```bash
git status
```

2. ЗАКОММить если нужно:
```bash
git add .
git commit -m "описание изменений"
```

3. ЗАПУШЬ:
```bash
git push origin main
```

4. ПОДОЖДИ деплоя (1-2 минуты)

5. ПРОВЕРЬ результат:
- https://baronkorfrus.github.io/pres_sfacall_ai/

### Проверка статуса деплоя

```bash
gh run list --repo BaronKorfRus/pres_sfacall_ai --limit 1
```

### Откат изменений

```bash
git log --oneline -5
git revert HEAD
git push
```

## URL проекта
- Главная: https://baronkorfrus.github.io/pres_sfacall_ai/
- Part 1 презентация: https://baronkorfrus.github.io/pres_sfacall_ai/presentations/part1/
- Part 1 конспект: https://baronkorfrus.github.io/pres_sfacall_ai/reading/part1/

## Troubleshooting

### 404 на GitHub Pages
1. Проверь что Pages включён в Settings
2. Проверь что workflow успешно завершился
3. Подожди 2-3 минуты

### Изменения не видны
1. Очисти кеш браузера (Cmd+Shift+R)
2. Проверь что push прошёл успешно
3. Подожди завершения GitHub Actions
