# InMemoryMapReduce
Проект написан на java. Запускается как и любой java проект.
В папке out\production\InMemoryMapReduce можно найти скомпилированный class файл.
В cmd (или bash (на линуксе не проверял, точно не скажу)) сменив директорию на out\production\InMemoryMapReduce пишете
java MapReduce (список параметров) чтобы запустить программу. 
Путь к файлам указывается абсолютный. map_script.exe, reduce_script.exe выполняют map и reduce соответственно. 
map_script находит только слова написанные латиницей разделенные пробелом, игнорируя все знаки припенания и цифры (g,o1. "home"-> go home).
src_file может содержать слова разделенные чем угодно.
