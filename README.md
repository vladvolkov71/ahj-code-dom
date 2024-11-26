[![Build status](https://ci.appveyor.com/api/projects/status/96c8n1lgof0g4xtd?svg=true)](https://ci.appveyor.com/project/vladvolkov71/ahj-code-dom)
[Сcылка на GitHub Pages](https://ludiamen.github.io/11-ahj-code-dom/)

Правила сдачи задания:

1. **Важно**: в рамках этого ДЗ нужно использовать менеджер пакетов yarn. Это значит, что никакого `package-lock.json` в репозитории быть не должно.
1. **Важно**: всё, включая картинки и стили, должно собираться через Webpack и выкладываться на GitHub Pages через AppVeyor.
1. В README.md должен быть размещён бейджик сборки и ссылка на GitHub Pages.
1. В качестве результата пришлите проверяющему ссылки на ваши GitHub-проекты.

---

### Игра с гоблинами

![](./pic/GracefulMiniatureBustard-small.gif)

#### Легенда

Вы решили доделать игру с гоблинами, поэтому нужно реализовать оставшуюся логику.

#### Описание

Нужно доделать игру с гоблинами, реализовав следующую логику:
1. Гоблин появляется в рандомной точке — набор точек фиксирован — ровно на 1 секунду.
1. Если пользователь успел за это время кликнуть на этой точке (попробуйте сделать custom-курсор в виде молотка), то:
    * пользователю засчитывается +1 балл,
    * гоблин пропадает из ячейки.
1. Если пользователь пропустил 5 появлений гоблинов, игра завершается.

Попробуйте реализовать всё не в виде единого скрипта, а разбив приложение на классы, каждый из которых ответственен за опредённую логику.

Всё должно собираться через Webpack и выкладываться на GitHub Pages через CI.

**В качестве результата пришлите проверяющему ссылку на ваш GitHub-проект. Не забудьте установить бейджик сборки.**
