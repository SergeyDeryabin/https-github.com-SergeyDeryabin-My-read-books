### Сорок(и более) штрихов о прочитанных(переведённых) книгах. 
### Штрих двенадцатый. 2015 год.

# Рут Кустерер. jMonkeyEngine 3.0 Руководство для начинающих. Разработка на обычном языке программирования Java профессиональных 3D-игр для настольных, веб и мобильных устройств.
## (Ruth Kusterer. jMonkeyEngine 3.0 Beginner's Guide. Develop professional 3D games for desktop, web, and mobile, all in the familiar Java programming language, ISBN 978-1-84951-646-4, Copyright © 2013 Packt Publishing)

p.s.

# Выдержка из книги:

## Предисловие

"Вы, мой храбрый герой, собираетесь отправиться за приключением, полным вызовов и рисков, но наградой в конце вашего путешествия будет богатство и восстановление мира на земле. Вы готовы? "
Вероятно, перед прочтением этой книги вы играли во множество игр, и с удовольствием принимали такие вызовы! Теперь вы столкнетесь с новым приключением. Вы создадите свою видеоигру. Будут проблемы, но движок jMonkeyEngine дает вам инструментарий для их преодоления. Эта книга введет Java-разработчиков в разработку 3D-игр и показывает, как движок jMonkeyEngine может сделать жизнь разработчика игр легче.
Обратите внимание на то, что эта книга не касается ни разработки 3D-моделей и звуков, ни творческого процесса придумывания сюжета оригинальной игры — прочтите приложение для некоторых связанных ресурсов. К концу этой книги вы будете готовы разработать 3D-игру и весело провести время во время разработки!

# Для кого предназначена эта книга?

Чтобы не обмануться в ожидании, скажем, что движок jMonkeyEngine не является одним из множества инструментов визуальной разработки, которые массово генерируют игры при помощи лишь нескольких щелчков мышью. Для создания действительно оригинальной игры, вам необходимо будет написать Java-код. Чтобы быть способным создать базовую сцену игры, вы должны хорошо знать следующие математические понятия:
- Декартовская система координат(The Cartesian coordinate system): когда вы помещаете персонаж или строение в сцену, то вы используете каждый раз координаты.
- Векторы(Vectors): каждый раз, когда вы заставляете управляемого компьютером врага обернуться, то вы используете векторы для задания углов и направлений. Каждый раз, когда враг следует за персонажем, то вы используете векторы для вычисления расстояния и скорости.
Где будет нужно, эта книга проведет вас через эти математические понятия и представит вам соответствующие встроенные методы и классы, которые решают эти задачи.

### Достижение цели

Часто успешные игры, такие как Minecraft, вдохновляют игроков становиться самим разработчиками игр. Примером игры, которая была вдохновлена игрой Minecraft, является игра Mythruna (http://mythruna.com/), игра открытого-мира, разработанная с использованием движка jMonkeyEngine.
...

## Что рассматривает эта книга?

**Глава 1 «Установка jMonkeyEngine»** помогает вам установить программное обеспечение и запустить пример приложения. 

**Глава 2 «Создание вашей первой 3D-сцены»** научит вас, как добавлять объекты и преобразовать их.
**Глава 3 «Взаимодействие с пользователем»** покажет, как управлять механикой игры в главном цикле.

**Глава 4 «Добавление персонажа к игре»** покажет, как загружать и преобразовывать модели.

**Глава 5 «Создание материалов»** демонстрирует, как манипулировать поверхностью объектов.

**Глава 6 «Забавы с физикой»** покажет, как сделать объекты действующими твердыми или тяжелыми.
 
**Глава 7 «Добавление вспышки к игре»** покажет базовые типы декоративных эффектов.

**Глава 8 «Создание пейзажей»** вводит ландшафты и природные эффекты.

**Глава 9 «Добавление звуков»** обучит, как интегрировать звуки и музыку.

**Глава 10 «Демонстрация миру вашей игры»** покажет, как сохранять, загружать, строить игры и заниматься их дистрибуцией.

**Приложение A «Что дальше?»** показывает, как сделать ваши игры забавными и бросающими вызов.

**Приложение Б «Дополнительные ресурсы для членов jMonkeys-сообщества»** представит вам более продвинутые пользовательские интерфейсы.

**Глава бесплатного скачивания «Игра в сети»** объясняет сетевое взаимодействие в многопользовательских играх. Эта глава доступна как глава бесплатного скачивания по адресу  http://www.packtpub.com/sites/default/files/downloads/6464OS_Free_Download_Chapter_Playing_on_the_Network.pdf

### Получите преимущество

Разработка игр включает широкий спектр способностей. Математика, программирование, графический дизайн, сочинение музыки и написание уровней. Подобно членам гильдии World of Warcraft, вы должны глубоко понимать инструменты вашей торговли, прежде чем вы отправитесь на свои поиски приключений. Необходимы навыки среднего или продвинутого уровня по языку Java и базовое понимание разработки мультимедиа и 3D-моделирования.
Однако, благодаря 3D-движкам, вы не должны повторно изобретать математическое колесо для каждой пишущейся вами 3D-игры. 3D-движки, такие как движок jMonkeyEngine ) решают для вас следующие задачи:
 - Преобразование(Transformation): поворот(rotating), масштабирование(scaling) и перемещение(moving) 3D-объектов
 - Проецирование(Projection): автоматическое преобразование данных 3D-сцены в 2D-изображения на экране 
 - Рендеринг(Rendering): современные передовые методы затенения и освещения поверхностей объектов

В дополнение к преобразованию, проецированию и рендерингу, есть набор внутренней функциональности, который является одним и тем же в каждой 3D-игре. Повторно используя проверенные реализации, вы экономите свой труд по ручному кодированию стандартных алгоритмов. Движок jMonkeyEngine включает много возможностей, которые могут быть найдены только в коммерческих игровых движках:
 - Граф 3D-сцены: структура данных, которая оптимизирована для хранения объектов 3D-сцены 
 - Главный цикл событий: модульный компонент, который управляет механикой игры и взаимодействиями
 - Поддержка загрузки и показа мультимедийных активов 
 - Поддержка обработки ввода данных пользователем и графических интерфейсов пользователя 
 - Объект интуитивной камеры, который отмечает точку обзора игрока
 - Моделирование физики, спецэффекты, многопользовательская сеть и многое другое

Движок jMonkeyEngine дает вам фору(преимущество) и поэтому у вас остается больше времени для кодирования компонент игры, которые делают вашу игру уникальной.

## Что потребуется для работы с книгой?

Требования изложены в главе 1 «Установка jMonkeyEngine».

## Книга:
https://www.packtpub.com/product/jmonkeyengine-3-0-beginner-s-guide/9781849516464

## Загрузка кода примеров для этой книги:
Нет.
## Загрузка цветных изображений для этой книги:
Нет.