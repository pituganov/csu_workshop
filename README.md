# Шаблон репозитория для курса

Шаблон с структурой проекта. Крайне желательно придерживаться ее.

## Описание


- `./notebooks` - директория с jupyter ноутбуками

- `./scripts` - директория под python скрипты

- `./requirements.txt` - зависимости, необходимые для запуска экспериментов

- `./README.md` - описание проекта

## Замечания

- Все самописные классы и функции должны объявляться в скриптах (не в ноутбуках!!). В ноутбке можно только импортировать их.

- Под каждый эксперимент/модель заводить отдельный ноутбук. Если у вас будет один длинный ноутбук с обучением всех моделей, то такой код при проверке будет игнорироваться

- Указывайте зависимости и их версии. Очень важно, чтобы при проверке задания код был рабочим!

- Убедитесь, что ваши эксперименты можно воспроизвести. Те, если новый человек будет запускать код с нуля, то он должен получить те же результаты что и вы

- Нельзя коммитить датасеты в репозиторий (особенно если они много весят)
