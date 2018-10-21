<table>
    <tr>
        <td> Read these guidelines in </td>
        <td><a href="/CONTRIBUTING.md"> English </a></td>
        <td><a href="/docs/chinese/CONTRIBUTING.md"> 中文 </a></td>
        <td><a href="/docs/russian/CONTRIBUTING.md"> русский </a></td>
        <td><a href="/docs/arabic/CONTRIBUTING.md"> عربى </a></td>
        <td><a href="/docs/spanish/CONTRIBUTING.md"> Español </a></td>
        <td><a href="/docs/portuguese/CONTRIBUTING.md"> Português </a></td>
    </tr>
</table>

# Как работать над задачами по написанию программного кода

### Изменения на GitHub
Каждая задача размещена в отдельном собственном markdown-файле. Такое разделение упрощает редактирование задач из GitHub.

Вы можете вносить изменения без каких-либо действий в вашей локальной системе.

После того, как вы выберете файл, который хотите править с помощью интерфейса GitHub, щелкните на значок карандаша для начала редактирования текста. Это автоматически создаст новую ветвь проекта, если вы сами еще этого не сделали.

Вы также можете создать копию проекта и вносить изменения локально на вашем компьютере. Для получения справки по этому вопросу, прочтите  [руководство по внесению правок](/CONTRIBUTING.md). 
### Шаблон задачи
Вот шаблон того, как выглядит markdown-файл задачи. 

````md
---
id: Уникальный номер (alphanumerical, MongoDB _id)
title: Название задачи
challengeType: 0
guideUrl: 'ссылка на руководство статьи'
videoUrl: 'ссылка на видео руководство'
---

## Описание
<section id='description'>
Описание задачи и того, что требуется выполнить
</section>

## Инструкции
<section id='instructions'>
Инструкции о том, что именно нужно сделать.
</section>
## тесты
<section id='tests'>

``` yml
- text: Should return "foo".
  testString: 'A stringified function using Chai asserts'
```

</section>

<div id='js-seed'>

```js
Код, отображаемый в редакторе по умолчанию 
```

</div>

### Перед тестированием
<div id='js-setup'>

```js
Тестовый установочный код.
```

</div>

</section>

### После теста
<div id='js-teardown'>

```js
Проверка кода на ошибки
```

</div>

</section>

## Решение
<section id='solution'>

```js
Код решения задачи
```

</section>
````

### Полезные ссылки
Создание и редактирование задач:
1. [Руководство по стилизации задачи](style-guide-for-curriculum-challenges.md) - как создавать и форматировать задачу
2. [Типы задач](https://github.com/freeCodeCamp/learn/blob/a5cb25704168aa37f59a582f0bb5a19b7bd89b46/utils/challengeTypes.js) - что означает номер задачи.
3. [Участие в FreeCodeCamp - написание тестов ES6](https://www.youtube.com/watch?v=iOdD84OSfAE#t=2h49m55s) - видео [Ethan Arrowood](https://twitter.com/ArrowoodTech) как он вносит правки в старую версию учебного плана.
