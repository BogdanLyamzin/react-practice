### Задание

1. Cоздайте новый React-проект с помощью "create-react-app".
2. Удалите из него лишние файлы.
3. Запустите его.
4. Создайте в папке "src" папку "components".
5. Создайте компонент "MainMenu", который будет представлять собой такую разметку:
```
<ul class="main-menu">
    <li class="main-menu-item">
        <a class="main-menu-link" href="">Home page</a>
    </li>
</ul>
```
Компонент будет получать пункты меню из пропа `items`. Тестовые данные можно взять [здесь](mainMenuItems.json)

Пропишите для компонента defaultProps и propTypes. 
Стилизацию сделайте с помощью SCSS-модулей.