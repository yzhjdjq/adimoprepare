# Настройка окружения для лаборатоных работ по АДиМО
## Для работы с файлами .ipynb
Эти файлы являются по сути json-объектами с разметрой markdown для\
отображаемого текста. Благодаря этому изучить их содержимое возможно\
в обычном блокноте.\
Открывая эти файлы в специальных решениях появляется возможность увидеть\
не только оформленное содержимое файла, но и выполнять код Python из полей,\
специально предназначенных для него. Такими средствами являются:
- [ Google Colab](google-colab.md "инструкция по настройке")
- [ Jupyter Notebook](jupyter-notebook.md "инструкция по настройке")
- [ VS Code](vs-code.md "инструкция по настройке")


### Google Colab
Является наиболее оптимальным решением для работы на разных устройствах\
так как поддерживает прямую работу с файлами из Google Drive.\
Кроме этого, нет необходимости иметь на этих устройствах Python\
и библотеки с которыми производится работа.\
Можно работать и без синхронизации, но в этом случае необходимо\
экспортировать результаты работы в .ipynb файлы и сохранить их в\
желаемое место. Если этого не сделать, то через не продолжительное\
время виртуальная машина, на базе которой происходила работа в сервисе,\
будет удалена вместе с созданными файлами.


### Jupyter Notebook
Предоставляет функционал по расшифровке .ipynb файлов и их корректному\
отображению. Требует установленного Python со всеми зависимостями.\
При этом сам он является python-библиотекой.

### VS Code
Так же как и Jupyter Notebook, умеет полноценно работать с .ipynb файлами.\
И аналогично требует наличия python со всеми зависимостями для выполнения\
написанного кода.

#### Python и его зависимости
Для выполнения работ в Jupyter Notebook и VS Code необходим\
установленный python. Также дополнительно к нему необходима\
библиотека pandas для работы с дата-сетами. Для математического\
обеспечения используется пакет numpy. Таким образом,\
минимальный список зависимостей:
- python
- pandas
- numpy


Для их установки можно воспользоваться опытом из предыдущего\
семестра или обратиться к [инструкции](python.md)
