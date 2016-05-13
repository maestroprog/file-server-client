**Описание**

Многопоточная передача файлов. Сборка сервера и клиента не отличается

**Требования**

* g++ 4.8.4+
* cmake 3.2+
* Gnu Make 3.81


**Сборка**

`$ cmake CMakeLists.txt
$ make`


**Запуск**

Для сервера

`$ ./FileTransmitServer <порт> <количество потоков> <размер очереди>`

Для клиент

`$ ./FileTransmitClient <ip> <порт> <имя файла>`
