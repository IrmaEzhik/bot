# Создай своего бота помощника
Создай несложный бот, используя все инструменты, которые вы изучили за фазу 0.

## Введение
Тебе предстоит создать бота помощника на любую тему, которая тебе интересна (например, как пережить коронавирус и не умереть со скуки, как обучиться js, как приготовить любимое блюдо...). Бот будет отвечать на несколько несложных вопросов. Делай коммиты на каждый новый функционал / исправление, пиши в коммит сообщении что ты в нем воплотил.

С чего же начать проект? Разобьем его на подзадачи / релизы!

## Releases:

### Release 0. HTML

Для начала необходимо накидать элементы на страницу. Хотелось бы видеть на сайте:
1. Текстовое поле для ввода вопроса
2. Кнопку, которая в дальнейшем будет куда-то отправлять текст из поля ввода.
3. Блок, в котором будут храниться вопросы и ответы. Таким образом этот блок и будет ботом. Теперь добавь несколько вопросов/ответов с каким-либо текстом. Добавленные элементы нужны для того, чтобы ты мог работать со стилями CSS еще до того, как научишь бота отвечать на вопросы по нажатию на кнопку.

### Release 1. Some CSS

Придумай на сколько стильным будет твой бот и как он будет выглядеть. Можешь подключить css framework, который тебе нравится (например https://bulma.io https://materializecss.com, https://getbootstrap.com/). Помощь в выборе https://2019.stateofcss.com/technologies/css-frameworks.

### Release 2. Flexbox

Сделай так, чтобы все твои элементы располагались по центру по горизонтали и вертикали. Да поможет тебе `flex`! А может хочешь попробовать `grid`? Или воспользоваться решением, которое предложено выбранным css framework?

### Release 3. @media

Уже выглядит неплохо, однако на смартфоне всё отображается не так красиво как хотелось бы. Исправь это :)

### Release 4. Listener

Пришло время вдохнуть жизнь в твой бот. Навесь событие на кнопку, чтобы содержимое текстового поля по нажатию на кнопку выводилось в консоль.

### Release 5. CreateElement

Создай новый элемент div по клику на ту же кнопку, в него добавляй текст из текстового поля. Затем полученный блок с текстом добавь в бот.

### Release 6. Array of answers
Настало время оживить твой бот. После введения вопроса в текстовое поле и нажатия на кнопку, бот должен ответить что-то плюс-минус логичное. Например: "Чем мне сегодня заняться?" ---> "А ты закончил проект по написанию бота?". Хмм...откуда же берутся ответы? Создаем (пока что хардкодим, пока у нас нет серверной части) массив возможных ответов в js файле.

### Release 7. Финальный штрих и самый важный
Напиши функцию, которая принимает два параметра: вопрос и массив ответов, и возвращает ответ в зависимости от слов упомянутых в вопросе. Объединяем все блоки вместе в один проект, проверяем что все работает как было задумано)

Делай пулл реквест и отправляй на проверку!

P.S. gitignore добавлен? Eslint подключен? Никаких лишних файлов и закомментированного кода?
