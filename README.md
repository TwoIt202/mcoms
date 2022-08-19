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
