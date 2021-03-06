<h1 align="center">
    <a href="https://lectrum.io" target="_blank" rel="noopener noreferrer">
        <img src="staticavicon/favicon-woodsmoke.svg" alt="Lectrum favicon" width="25" />
    </a>
    Интенсив по Webpack
</h1>
<br>

<div align="center">
    <!-- Package version -->
    <img src="https://img.shields.io/github/package-json/v/lectrum/webpack-intensive.svg?longCache=true&style=flat-square"
        alt="Package version" />
    <!-- Last commit -->
    <img src="https://img.shields.io/github/last-commit/lectrum/webpack-intensive.svg?longCache=true&style=flat-square" alt="Last commit"
    />
    <!-- Dependencies -->
    <img src="https://img.shields.io/badge/dependencies-up%20to%20date-brightgreen.svg?longCache=true&style=flat-square" alt="Dependencies"
    />
    <!-- Contributors welcome -->
    <img src="https://img.shields.io/badge/contributions-welcome-orange.svg?longCache=true&style=flat-square" alt="Last update"
    />
</div>
<div align="center">
    <!-- Наш Facebook -->
    <a href="https://www.facebook.com/lectrum">
        <img src="https://img.shields.io/badge/%D0%9F%D0%BE%D0%B4%D0%BF%D0%B8%D1%81%D1%8B%D0%B2%D0%B0%D0%B9%D1%81%D1%8F%20%D0%BD%D0%B0%20%D0%BD%D0%B0%D1%88-Facebook-blue.svg?longCache=true&style=for-the-badge&link=https://www.facebook.com/lectrum"
            alt="Подписывайся на наш Facebook" />
    </a>
</div>
<br>

<h3 align="center">
    👋🏼 Привет и добро пожаловать!
</h3>
<p>
    📸 Вместе мы изучим webpack целиком и полностью, причём на этом не остановимся! Пристегни ремни — будет интересно!
</p>
<br>
<p>
    👨🏼‍🔬 В этой инструкции ты узнаешь как настроить и запустить проект.
</p>
<br>

## 📜 Содержание

<img align="right" width="70" src="staticogos/webpack.png">

-   [🚀 Инструкция по запуску проекта](#-инструкция-по-запуску-проекта)
-   [🤔 FAQ](#-faq)
<br>

### 🚀 Инструкция по запуску проекта

> Список поддерживаемых нами операционных систем [можно найти здесь](https://github.com/Lectrum/FAQ#%D0%9A%D0%B0%D0%BA%D0%B8%D0%B5-%D0%BE%D0%BF%D0%B5%D1%80%D0%B0%D1%86%D0%B8%D0%BE%D0%BD%D0%BD%D1%8B%D0%B5-%D1%81%D0%B8%D1%81%D1%82%D0%B5%D0%BC%D1%8B-%D0%BF%D0%BE%D0%B4%D0%B4%D0%B5%D1%80%D0%B6%D0%B8%D0%B2%D0%B0%D1%8E%D1%82%D1%81%D1%8F-%D0%BE%D0%B1%D1%83%D1%87%D0%B0%D1%8E%D1%89%D0%B8%D0%BC%D0%B8-%D0%BF%D1%80%D0%BE%D0%B5%D0%BA%D1%82%D0%B0%D0%BC%D0%B8-%D0%BA%D0%BE%D0%BC%D0%BF%D0%B0%D0%BD%D0%B8%D0%B8-lectrum).

На интенсиве мы будем применять особый скрипт синхронизации, чтобы всегда быть на одной волне. Синхронизация поможет тебе в любой момент получить код к проекта преподавателя в свой проект одной командой **`npm run checkpoint`**.

> При каждом выполнении команды синхронизации твой код будет сохранён в ветке my-backup-1, my-backup-2 и тд, чтобы потом можно было вернутся и поработать со своим кодом.

Чтобы настроить проект и синхронизацию следуй инструкции:

1. [Скачай и установи](https://nodejs.org/en/) последнюю **`LTS-версию Node 10.14.1`**:
2. Выполни в консоли **`node -v`** и убедись, что установленная версия **`Node.js`** не ниже **`10.14.1`**;
3. Выполни в консоли **`npm -v`** и убедись, что установленная версия **`npm`** не ниже **`6.4.1`**;
> ❗️ Мы поддерживаем только последние **`LTS-версии Node.js`** (текущая LTS — **`Node 10.14.1`**). Мы не даём гарантий работы на других версиях Node. Если у тебя не работает, в первую очередь проверь версию Node.js!
4. [Скачай и установи Git](https://git-scm.com/downloads), если его нет на компьютере;
5. Выполни в консоли **`git --version`**, чтобы проверить версию установленного Git, должно быть не ниже **`2.19.0`**;
6. Склонируй этот проект:

```bash
git clone https://github.com/Lectrum/webpack-intensive.git
```

7. Перейди в проект, выполнив команду:

```bash
cd webpack-intensive
```

8. В терминале, находясь в директории с текущим проектом, выполни команду:

```bash
npm install
```

9. Открой файл **`package.json`**, в поле **`version`** должно быть такое значение **`"0.0.0"`**;
10. Выполни скрипт синхронизации с помощью команды:

```bash
npm run checkpoint
```

11. Теперь в **`package.json`**, в поле **`version`** должно быть такое значение **`"1.0.0"`**.


##### 👉🏼 Хозяйке на заметку
> Все доступные команды и возможности сгенерированного проекта можно [найти по этой ссылке](https://github.com/Lectrum/generator-ui#-%D0%9A%D1%80%D0%B0%D1%82%D0%BA%D0%B8%D0%B9-%D0%BE%D0%B1%D0%B7%D0%BE%D1%80-%D0%BA%D0%BE%D0%BC%D0%B0%D0%BD%D0%B4-%D0%B4%D0%BB%D1%8F-%D1%81%D0%B3%D0%B5%D0%BD%D0%B5%D1%80%D0%B8%D1%80%D0%BE%D0%B2%D0%B0%D0%BD%D0%BD%D0%BE%D0%B3%D0%BE-%D0%BF%D1%80%D0%BE%D0%B5%D0%BA%D1%82%D0%B0).
<br>

### 🤔 FAQ

Ответы на часто задаваемые вопросы можно найти [здесь](https://github.com/Lectrum/FAQ#-faq).
<br>

### Лицензия

MIT © [Lectrum](https://lectrum.io)

<div align="center">
  <!-- Сделано с любовь -->
    <img src="https://img.shields.io/badge/%D0%A1%D0%B4%D0%B5%D0%BB%D0%B0%D0%BD%D0%BE%20%D1%81-%F0%9F%96%A4-red.svg?longCache=true&style=for-the-badge&colorA=000&colorB=fedcba"
      alt="Сделано с любовь" />
</div>
