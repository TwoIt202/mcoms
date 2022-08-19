# Documentation (en)


Autor: Vagif Babayev (two-it2022)

Email: kodland.group@gmail.com

Version: 1.0


# 1. Installing

Open the CMD and write inside: pip install mcoms
Create file [your_file_name].py and write inside: 

import mcoms or from mcoms import *

# 2. Commands

FileDialog(*type) - Opening the dialog window. Type: save_as, open

fileRemove(*file) - Removing the file.

PlayAudio(*file) - Playing the MP3 and WAV file.

printS(*text, *sleepTime) - Printing the text a few time.

loadText(*txt, *sleepTime) - Loading text print.

loadSs(*style, *Sss, *timeSleep) - Load the styles. Styles: square, line, circle

LetterEdit(*text, *style) - Letter style editing. Styles: up, down

fileRead(*file) - Reading file inside text.

fileWrite(*file, *text) - Writing text in file.

fileCreate(*name) - Creating a file.

fileRename(*oldName, newName) - Renaming the file name

mailReg(*userR, *passwordR) - Register mail user.

sendToGmail(*to, *message) - Sending message to user mail in Gmail.

sendToMail(*to, *message) - Sending message to user mail in Mail.

Translate(*fromL, *toL, *text) - Translating text from language to other language.

System(*typeS) - Shows sytem data. Types: display, ip-address

MessageWindow(*type, *title, *message) - Creating message window. Types: info, warning, error, ask, ask_ok_cancel, ask_retry

timer(*type, *count) - Timer of seconds, minutes and hours. Types: s-second, m-minute, h-hours

start_server() - Starting website on hosting.

create_room(*address, *name, *text) - Create a new index.

connect(*address, *name, *server_name) - Connecting to index.

printC(*tx, *c) - Print colored text.














# Документация (ru)


Автор: Vagif Babayev (two-it2022)

Почта: kodland.group@gmail.com

Версия: 1.0


# 1. Установка

Откройте Командную Строку и напишите внутрь: pip install mcoms
Создайте файл [имя_вашего_файла].py и напишите внутрь: 

import mcoms или from mcoms import *

# 2. Команды

FileDialog(*type) - Открывает диалоговое окно. Тип: save_as, open

fileRemove(*file) - Удаляет файл.

PlayAudio(*file) - Проигрывает MP3 или WAV файл.

printS(*text, *sleepTime) - Выводит текст через заданное время.

loadText(*txt, *sleepTime) - Выводит текст-загрузку.

loadSs(*style, *Sss, *timeSleep) - Загужает стили. Стили: square, line, circle

LetterEdit(*text, *style) - Изменяет тип буквы. Типы: up, down

fileRead(*file) - Прочитывает внутренный текст файла.

fileWrite(*file, *text) - Изменяет текст файла.

fileCreate(*name) - Создаёт файл.

fileRename(*oldName, newName) - Переименовает имя файла.

mailReg(*userR, *passwordR) - Регистрирует почту пользователя.

sendToGmail(*to, *message) - Отправляет сообщение на почту в Gmail.

sendToMail(*to, *message) - Отправляет сообщение на почту в Mail.

Translate(*fromL, *toL, *text) - Переводит текст с заданного на заданный язык.

System(*typeS) - Показывает данные о системе. Типы: display, ip-address

MessageWindow(*type, *title, *message) - Создает окно "Сообщение". Типы: info, warning, error, ask, ask_ok_cancel, ask_retry

timer(*type, *count) - Таймер секунд, минут и часов. Типы: s-секунда, m-минута, h-часы

start_server() - Запускает сайт на хостинге.

create_room(*address, *name, *text) - Создаёт индекс.

connect(*address, *name, *server_name) - Подключаеться к индексу.

printC(*tx, *c) - Выводит раскрашенный текст.
