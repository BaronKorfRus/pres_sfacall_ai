# Презентация на GitHub Pages

Репозиторий подготовлен для публикации через GitHub Pages.

## Что уже настроено

- `/.github/workflows/pages.yml` — автодеплой на GitHub Pages при пуше в `main` или `master`.
- `/index.html` — главная страница-навигация.
- `/presentations/part1/` — презентация «Часть 1».
- `/reading/part1/` — красивое отображение markdown-конспектов.
- `/content/part1.md` — исходный markdown-файл.

## Структура репозитория

```text
.
├── assets/                  # изображения и медиа
├── content/                 # исходные .md конспекты
├── presentations/
│   └── part1/               # слайды части 1
├── reading/                 # красивые HTML-страницы чтения markdown
│   └── part1/
├── text/                    # меню для перехода к конспектам
└── index.html               # навигация по материалам
```

## Какие будут URL после публикации

Замените `<USERNAME>` и `<REPO>`:

- Презентация: `https://<USERNAME>.github.io/<REPO>/`
- Презентация Part 1: `https://<USERNAME>.github.io/<REPO>/presentations/part1/`
- Чтение Part 1 (HTML): `https://<USERNAME>.github.io/<REPO>/reading/part1/`
- Markdown Part 1: `https://<USERNAME>.github.io/<REPO>/content/part1.md`

## Как включить Pages в GitHub

1. Запушить репозиторий в GitHub.
2. Открыть `Settings -> Pages`.
3. В `Build and deployment` выбрать `Source: GitHub Actions`.
4. Дождаться завершения workflow `Deploy to GitHub Pages`.

## Как добавить новую часть

1. Создайте `content/part2.md` с текстом конспекта
2. Скопируйте `presentations/part1/index.html` в `presentations/part2/` и отредактируйте
3. Скопируйте `reading/part1/index.html` в `reading/part2/` и обновите путь к markdown
4. Добавьте карточку в `index.html` на главной странице
