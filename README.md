# 📁 Работа с git и bash

📌 При наличии доступа к серверу, у тестировщика есть возможность просматривать логи и другие артефакты с использованием bash комманд.

Ниже представлен список комманд в Git Bash - терминале, которые были выполнены для перемещения между директориями, создания и удаления папок и файлов, а также поиска и замены текста в файлах.

<h3>Задача 1:</h3>
<table>
  <tr>
    <th>Задание</th>
    <th>Выполненная команда</th>
  </tr>
  <tr>
    <td>Создать домашнюю директорию через терминал</td>
    <td>$ mkdir homedir</td>
  </tr>
  <tr>
    <td>Открыть домашнюю директорию через терминал</td>
    <td>$ cd homedir</td>
  </tr>
  <tr>
    <td>Определить имя папки, в которой вы находитесь</td>
    <td>$ pwd</td>
  </tr>
  <tr>
    <td>Создать внутри этой папки каталог с именем test1</td>
    <td>$ mkdir test1</td>
  </tr>
  <tr>
    <td>Перейти в папку test1</td>
    <td>$ cd test1</td>
  </tr>
  <tr>
    <td>Создать файл 1,2 и 3 внутри каталога test1</td>
    <td>$ touch file1.txt file2.txt file3.txt</td>
  </tr>
  <tr>
    <td>Проверить содержимое каталога test1</td>
    <td>$ ls 
      <br>file1.txt  file2.txt  file3.txt</td>
  </tr>
  <tr>
    <td>Перейти в домашнюю директорию</td>
    <td>$ cd ..</td>
  </tr>
  <tr>
    <td>Создать папку test2 внутри домашней директории</td>
    <td>$ mkdir test2</td>
  </tr>
  <tr>
    <td>Удалить папку test2</td>
    <td>$ rmdir test2</td>
  </tr>
  <tr>
    <td>Удалить файл 2 из папки test1</td>
    <td>$ rm test1/file2.txt</td>
  </tr>
  <tr>
    <td>Создать папку в домашней директории test3 и добавить в нее два файла</td>
    <td>$ mkdir test3 && touch $_/file4.txt $_/file5.txt</td>
  </tr>
  <tr>
    <td>Удалить папку test3</td>
    <td>$ rm -r test3</td>
  </tr>
  <tr>
    <td>Создать папку test4 в домашней директории</td>
    <td>$ mkdir test4</td>
  </tr>
  <tr>
    <td>Переместить файлы 1 и 3 из папки test1 в папку test4</td>
    <td>$ mv test1/file1.txt test1/file3.txt test4/</td>
  </tr>
  <tr>
    <td>Добавить в файл 1 три строки со словами line</td>
    <td>$ echo -e "line\nline\nline" >> test4/file1.txt</td>
  </tr>
  <tr>
    <td>Посмотреть содержимое файла 1</td>
    <td>$ cat test4/file1.txt</td>
  </tr>
  <tr>
    <td>Добавьте в файл 3 три строки со словами line</td>
    <td>$ echo -e "line\nline\nline" >> test4/file3.txt</td>
  </tr>
  <tr>
    <td>Просмотрите содержимое двух файлов (1 и 3) сразу</td>
    <td>$ cat test4/file1.txt test4/file3.txt</td>
  </tr>
  <tr>
    <td>Используя один из редакторов замените все строки в файле 1</td>
    <td>$ nano test4/file1.txt</td>
  </tr>
</table>
<hr>
