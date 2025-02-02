<h1 align="center">🎬 YouTube Video Downloader</h1>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.7%2B-blue?logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/License-MIT-green?logo=git" alt="License">
</p>

<div align="center">
  <strong>Скачивайте видео с YouTube в один клик!</strong><br>
  Поддержка высокого качества, выбор пути сохранения, кастомизация имени файла.
</div>

---

<!-- Оглавление -->
<h2>📋 Содержание</h2>
<ul>
  <li><a href="#установка">Установка</a></li>
  <li><a href="#использование">Использование</a></li>
  <li><a href="#примеры">Примеры</a></li>
  <li><a href="#лицензия">Лицензия</a></li>
</ul>

---

<!-- Установка -->
<h2 id="установка">🛠 Установка</h2>
<pre>
<code># 1. Клонировать репозиторий
git clone https://github.com/your-username/youtube-downloader.git

# 2. Перейти в директорию проекта
cd youtube-downloader

# 3. Установить зависимости
pip install -r requirements.txt</code>
</pre>

---

<!-- Использование -->
<h2 id="использование">🚀 Использование</h2>
<div>
  <h3>Доступные аргументы:</h3>
  <table>
    <tr>
      <th>Аргумент</th>
      <th>Описание</th>
    </tr>
    <tr>
      <td><code>URL</code></td>
      <td>Обязательный. Ссылка на YouTube-видео</td>
    </tr>
    <tr>
      <td><code>-o, --output-path</code></td>
      <td>Путь для сохранения (по умолчанию: текущая директория)</td>
    </tr>
    <tr>
      <td><code>-f, --filename</code></td>
      <td>Кастомное имя файла (без расширения)</td>
    </tr>
  </table>
</div>

---

<!-- Примеры -->
<h2 id="примеры">📂 Примеры</h2>
<h3>Базовая команда:</h3>
<pre>
<code>python downloader.py "https://www.youtube.com/watch?v=dQw4w9WgXcQ"</code>
</pre>

<h3>С кастомными параметрами:</h3>
<pre>
<code>python downloader.py \\
  --output-path "/home/user/videos" \\
  --filename "awesome_video" \\
  "https://www.youtube.com/watch?v=dQw4w9WgXcQ"</code>
</pre>

---

<!-- Лицензия -->
<h2 id="лицензия">📜 Лицензия</h2>
<p>
  <a href="LICENSE">
    <img src="https://github.com/BOCXO2" alt="MIT License">
  </a>
</p>

<div align="center">
  <p>🎉 Спасибо за использование! Если есть вопросы, создавайте <a href="https://github.com/bocxo2/youtube-downloader/issues">issue</a></p>
  <p>Сделано с ❤️ и 10 чашками кофе</p>
</div>
