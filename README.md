# Flutter Developer Resume

Репозиторий оформлен в стиле `resume as code`: основное содержимое резюме хранится в YAML, а GitHub Pages рендерит его в сайт на Jekyll с темой `garth`.

## Структура

- [_data/resume.yml](/home/jooon/resume/_data/resume.yml) — основной источник данных резюме
- [index.html](/home/jooon/resume/index.html) — Jekyll-шаблон главной страницы
- [assets/styles.scss](/home/jooon/resume/assets/styles.scss) — кастомные стили поверх темы
- [_config.yml](/home/jooon/resume/_config.yml) — конфигурация GitHub Pages и темы

## Как редактировать

Обновляй текст резюме в [_data/resume.yml](/home/jooon/resume/_data/resume.yml):

- `profile` — позиция и краткое описание
- `work_preferences` — формат работы и зарплатные ожидания
- `skills` — стек
- `highlights` — сильные стороны
- `experience` — коммерческий опыт и практика
- `contacts` — контакты

## Локальный запуск

```bash
bundle install
bundle exec jekyll serve
```

После запуска сайт будет доступен локально, а на GitHub Pages будет собираться через `remote_theme: daviddarnes/garth`.

## Источник идеи

Подход вдохновлён YAMLResume:

- https://github.com/yamlresume/yamlresume
- https://yamlresume.dev/docs
