# Тишина в библиотеке

# "Генератор отчетов по книгам"
<p>Разработать программу на JavaScript, которая создает и обрабатывает объекты, представляющие книги в библиотеке. Программа должна позволять добавлять книги в библиотеку, удалять их, а также генерировать различные отчеты.</p>

# Задачи:

<h2>Создание структуры данных книги:</h2>

<ul>
<li>Создайте объекты для книг с полями: название, автор, год издания, жанр и количество страниц.
Предусмотрите функцию для добавления книги в библиотеку. Библиотека должна быть представлена в виде массива объектов.</li></ul>

<h2>Функциональность библиотеки:</h2>
<ul>
<li>Реализуйте функцию для удаления книги из библиотеки по названию.</li>
<li>Реализуйте функцию для поиска книг по автору и вывода списка всех книг этого автора.</li>
<li>Создайте функцию для фильтрации книг по жанру.</li></ul>
<h2>Генерация отчетов:</h2>
<ul>
<li>Разработайте функцию для генерации отчета о количестве книг каждого жанра в библиотеке.
<li>Реализуйте функцию для генерации отчета о среднем количестве страниц по всем книгам в библиотеке.
<li>Дополнительно! Создайте функцию, которая выводит список всех книг, отсортированный по году издания, от новых к старым.</li></ul>

# Добавление книг в библиотеку
addBook("Хоббит", "Дж. Р. Р. Толкиен", 1937, "Фэнтези", 310);
addBook("Гарри Поттер и философский камень", "Дж. К. Роулинг", 1997, "Фэнтези", 223);
addBook("1984", "Джордж Оруэлл", 1949, "Антиутопия", 328);
# Поиск книг по автору
console.log(findBooksByAuthor("Дж. Р. Р. Толкиен"));
# Фильтрация книг по жанру
console.log(filterBooksByGenre("Фэнтези"));
# Генерация отчета по количеству книг каждого жанра
console.log(genreReport());
# Генерация отчета по среднему количеству страниц
console.log(`Среднее количество страниц: ${averagePagesReport()}`);
# Удаление книги и вывод обновленной библиотеки
removeBook("1984"); console.log(library);