# Sberbank2Excel

Утилита для конвертации выписки Свербанка по карте из формата PDF в формат Excel

Автор: ev2geny собака gmail.com

Ссылка на утилиту в системе github https://github.com/Ev2geny/Sberbank2Excel

Ссылка для скачивания скомпилированного файла, готового к запуску на Windows https://github.com/Ev2geny/Sberbank2Excel/releases/latest

## Как пользоваться

Для использования утилиты сначала надо сконвертировать выписку PDF в текстовый формат используя foxit PDF reader  https://www.foxitsoftware.com/pdf-reader/

### Подготовка
#### sberbankPDFtext2ExcelGUI.exe

1. Скачать последнюю версию  **sberbankPDFtext2ExcelGUI.zip** https://github.com/Ev2geny/Sberbank2Excel/releases/latest 
2. Разархивировать ZIP файл в отдельную директорию и найти *sberbankPDFtext2ExcelGUI.bat*

#### foxit PDF reader
1. Установить foxit PDF reader  https://www.foxitsoftware.com/pdf-reader/

### Конвертация 

**Шаг 1** Окройте выписку Сбербанка по карте в формате PDF используюя заранее установленный foxit PDF reader

**Шаг 2** Сохраните файл в текстовом формате (File ==> Save as ==> computer ==> (Выберете папку)). При сохранении выберете формат **TXT files (*.txt)**

**Шаг 3** Запустите **sberbankPDFtext2ExcelGUI.bat**

**Шаг 4** Выберите один или несколько сконвертированных текстовых файлов

**Шаг 5** Нажмите "Сконвертировать выбранные файлы"

**Результат:** утилита создаст файлы с расширением .xlsx 
