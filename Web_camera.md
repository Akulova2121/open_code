# Чек лист
---
1. Запустить программу
2. Проверить на соответствиие дизайна программы в тестовой документации в части палитра цветов окон
3. Проверить функционирования видеопотока
4. Проверить на соответствиие дизайна кнопки в тестовой документации в части палитра цвета и размер шрифта
5. Проверить функционирование кнопки (сделать снимок)
6. Проверить снимок на соответствие с дизайном в тестовой документации
7.  Сделать 10 снимков

# Тест-кейсы
---
![Тест_1](https://github.com/Akulova2121/open_code/blob/%D0%98%D0%B7%D0%BE%D0%B1%D1%80%D0%B0%D0%B6%D0%B5%D0%BD%D0%B8%D1%8F/%D0%A2%D0%B5%D1%81%D1%82_1.png)


![Тест_2](https://github.com/Akulova2121/open_code/blob/%D0%98%D0%B7%D0%BE%D0%B1%D1%80%D0%B0%D0%B6%D0%B5%D0%BD%D0%B8%D1%8F/%D0%A2%D0%B5%D1%81%D1%82_2.png)


![Тест_3](https://github.com/Akulova2121/open_code/blob/%D0%98%D0%B7%D0%BE%D0%B1%D1%80%D0%B0%D0%B6%D0%B5%D0%BD%D0%B8%D1%8F/%D0%A2%D0%B5%D1%81%D1%82_3.png)


![Тест_4](https://github.com/Akulova2121/open_code/blob/%D0%98%D0%B7%D0%BE%D0%B1%D1%80%D0%B0%D0%B6%D0%B5%D0%BD%D0%B8%D1%8F/%D0%A2%D0%B5%D1%81%D1%82_4.png)


![Тест_5](https://github.com/Akulova2121/open_code/blob/%D0%98%D0%B7%D0%BE%D0%B1%D1%80%D0%B0%D0%B6%D0%B5%D0%BD%D0%B8%D1%8F/%D0%A2%D0%B5%D1%81%D1%82_5.png)


![Тест_6](https://github.com/Akulova2121/open_code/blob/%D0%98%D0%B7%D0%BE%D0%B1%D1%80%D0%B0%D0%B6%D0%B5%D0%BD%D0%B8%D1%8F/%D0%A2%D0%B5%D1%81%D1%82_6.png)


![Тест_7](https://github.com/Akulova2121/open_code/blob/%D0%98%D0%B7%D0%BE%D0%B1%D1%80%D0%B0%D0%B6%D0%B5%D0%BD%D0%B8%D1%8F/%D0%A2%D0%B5%D1%81%D1%82_7.png)


# Баг-репорт
---
<table>
    <thead>
        <tr>
            <th>№</th>
            <th>Заголовок</th>
            <th>Описание ошибки</th>
            <th>Окружение</th>
            <th>Начальные условия</th>
            <th>Шаги</th>
            <th>Ожидаемый</th>
            <th>Результат</th>
            <th>Вложение</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td align="center">1</td>
            <td align="left">Видеопоток отображается не стабильно</td>
            <td align="left">В открывшейся программе видеопоток отбражается с нарушениями (с задержками)</td>
            <td align="center">Windows 10 Pro Сборка ОС 19045.3086</td>
            <td align="left">1. Открыта папка "web-camera"</td>
            <td align="left">1. Кликнуть два раза на файл "WebCamera.exe"</td>
            <td align="left">Видеопоток "отображается" без задержек</td>
            <td align="left">Видеопоток "отображается" с задержками</td>
             <td align="center">
                 <p><a href="https://github.com/Akulova2121/open_code/blob/%D0%98%D0%B7%D0%BE%D0%B1%D1%80%D0%B0%D0%B6%D0%B5%D0%BD%D0%B8%D1%8F/20230709_132803.mp4">Web_camera</a></p> 
                 <p><a href="https://github.com/Akulova2121/open_code/blob/%D0%98%D0%B7%D0%BE%D0%B1%D1%80%D0%B0%D0%B6%D0%B5%D0%BD%D0%B8%D1%8F/20230709_133256.mp4">hlsplayer</a></p>
             </td>
        </tr>
     </tbody>
</table>



<table>
    <thead>
        <tr>
            <th>№</th>
            <th>Заголовок</th>
            <th>Описание ошибки</th>
            <th>Окружение</th>
            <th>Начальные условия</th>
            <th>Шаги</th>
            <th>Ожидаемый</th>
            <th>Результат</th>
            <th>Вложение</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td align="center">2</td>
            <td align="left">Чёрный контур вокруг кнопки "СДЕЛАТЬ СНИМОК"</td>
            <td align="left">Образуется чёрный контур вокруг кнопки "СДЕЛАТЬ СНИМОК" при клике на неё во время зависания потока</td>
            <td align="center">Windows 10 Pro Сборка ОС 19045.3086</td>
            <td align="left"><p>1. Открыта папка "web-camera"</p> <p>2. Запущена программа "WebCamera"</p></td>
            <td align="left"><p>1. Навести курсор на кнопку "СДЕЛАТЬ СНИМОК"</p> <p>2. Кликнуть на кнопку "СДЕЛАТЬ СНИМОК"</p></td>
            <td align="left">Кнопка "отображается" без изменений</td>
            <td align="left">Образуется чёрный контур вокруг кнопки</td>
             <td align="center"><a href="https://github.com/Akulova2121/open_code/blob/%D0%98%D0%B7%D0%BE%D0%B1%D1%80%D0%B0%D0%B6%D0%B5%D0%BD%D0%B8%D1%8F/Screenshot_5.png">Скрин</a>    
             </td>
        </tr>
     </tbody>
</table>


<table>
    <thead>
        <tr>
            <th>№</th>
            <th>Заголовок</th>
            <th>Описание ошибки</th>
            <th>Окружение</th>
            <th>Начальные условия</th>
            <th>Шаги</th>
            <th>Ожидаемый</th>
            <th>Результат</th>
            <th>Вложение</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td align="center">3</td>
            <td align="left">Вместо снимка "отображается" черный кадр</td>
            <td align="left">"Отображается" черный кадр при клике на кнопку "СДЕЛАТЬ СНИМОК" </td>
            <td align="center">Windows 10 Pro Сборка ОС 19045.3086</td>
            <td align="left"><p>1. Открыта папка "web-camera"</p> <p>2. Запущена программа "WebCamera"</p></td>
            <td align="left"><p>1. Навести курсор на кнопку "СДЕЛАТЬ СНИМОК"</p> <p>2. "Кликнуть" на кнопку "СДЕЛАТЬ СНИМОК"</p></td>
            <td align="left">"На кадре отображается изображение</td>
            <td align="left">Отображается черный кадр</td>
             <td align="center"><a href="https://github.com/Akulova2121/open_code/blob/%D0%98%D0%B7%D0%BE%D0%B1%D1%80%D0%B0%D0%B6%D0%B5%D0%BD%D0%B8%D1%8F/Screenshot_5.png">Скрин</a>    
             </td>
        </tr>
     </tbody>
</table>

<table>
    <thead>
        <tr>
            <th>№</th>
            <th>Заголовок</th>
            <th>Описание ошибки</th>
            <th>Окружение</th>
            <th>Начальные условия</th>
            <th>Шаги</th>
            <th>Ожидаемый</th>
            <th>Результат</th>
            <th>Вложение</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td align="center">4</td>
            <td align="left">Кнопка "СДЕЛАТЬ СНИМОК"не соответствует дизайну</td>
            <td align="left">Кнопка "СДЕЛАТЬ СНИМОК" в приложении не соответствует дизайну в текстовой документации</td>
            <td align="center">Windows 10 Pro Сборка ОС 19045.3086</td>
            <td align="left"><p>1. Открыта папка "web-camera"</p> <p>2. Запущена программа "WebCamera"</p></td>
            <td align="left"><p>Проверить на соответствие палитры цвета и шрифта кнопки с дизайном указанным в технической документации</p></td>
            <td align="left">Кнопка соответсвует дизайну</td>
            <td align="left">Кнопка не соответсвует дизайну</td>
             <td align="center"><a href="https://github.com/Akulova2121/open_code/blob/%D0%98%D0%B7%D0%BE%D0%B1%D1%80%D0%B0%D0%B6%D0%B5%D0%BD%D0%B8%D1%8F/Screenshot_7.png">Скрин</a>    
             </td>
        </tr>
     </tbody>
</table>

<table>
    <thead>
        <tr>
            <th>№</th>
            <th>Заголовок</th>
            <th>Описание ошибки</th>
            <th>Окружение</th>
            <th>Начальные условия</th>
            <th>Шаги</th>
            <th>Ожидаемый</th>
            <th>Результат</th>
            <th>Вложение</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td align="center">5</td>
            <td align="left">Визуальный размер кадра не соответствует дизайну тех.документации</td>
            <td align="left">Визуальный размер кадра в приложении не соответствует дизайну в текстовой документации</td>
            <td align="center">Windows 10 Pro Сборка ОС 19045.3086</td>
            <td align="left"><p>1. Открыта папка "web-camera"</p> <p>2. Запущена программа "WebCamera"</p> <p>3. Нажата кнока "СДЕЛАТЬ СНИМОК"</p> <p>4.В нижней части программы "отображается" снимок</p></td>
            <td align="left"><p>Проверить на "соответствие" палитры цветов окна программы с дизайном "указанным" в технической документации</p></td>
            <td align="left">Кадр соответсвует дизайну</td>
            <td align="left">Кадр не соответсвует дизайну</td>
             <td align="center"><a href="https://github.com/Akulova2121/open_code/blob/%D0%98%D0%B7%D0%BE%D0%B1%D1%80%D0%B0%D0%B6%D0%B5%D0%BD%D0%B8%D1%8F/Screenshot_7.png">Скрин</a>    
             </td>
        </tr>
