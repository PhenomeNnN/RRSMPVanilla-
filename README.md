# RUST & RADISH · SMP Vanilla+

Публичная вики сервера на Material for MkDocs. В этом проекте только материалы сайта: никакие конфиги сервера, базы игроков и рецепты BreweryX не публикуются.

## Локальная сборка

Python 3.12:

```sh
python -m pip install -r requirements.txt
python -m mkdocs serve
```

Строгая проверка: `python -m mkdocs build --strict`.

## GitHub Pages

Workflow `.github/workflows/pages.yml` собирает сайт при push в main и публикует его в Pages. В Settings → Pages выберите Source: GitHub Actions. В репозитории должны быть разрешены Actions. Сборку также можно запустить вручную через workflow_dispatch.

Текущий URL в mkdocs.yml соответствует репозиторию `PhenomeNnN/RRSMPVanilla-`. После переименования обновите `site_url`, `repo_url` и `repo_name`. Визуальное название сайта — SMP Vanilla+.

## Что редактировать

- Команды: `docs/commands.md`.
- Гайды: `docs/guides/`.
- Утверждённые правила: `docs/rules.md` (сейчас страница ожидания, без выдуманных наказаний).
- Соцсети: `docs/links.md` (добавить реальные адреса).
- Меню и оформление: `mkdocs.yml`, `docs/stylesheets/extra.css`.

## Основание материалов

Редакция 24.10.2026. Команды и параметры сверены с локальной рабочей копией SMPVANILLA: Towny Standard, CarbonChat, ValhallaMMO 1.10.3 и BreweryX. Рабочая копия не подтверждает применение на удалённом сервере. Страница Classic различает общую механику пакета и проверенные настройки профиля. Перед объявлением вики окончательным регламентом сверить команды обычным игроком, импорт Classic и действующие настройки Towny.
