# ItSALive
Этот небольшой код защищает статистику Яндекс Метрики (и GA) от действий рефспам-ботов. Эти боты в виртуальном браузере загружают страницы вашего сайта с поддельной референс-ссылкой. Затем они выполняют Javascript на странице и, соответственно, код Метрики и тут же закрывают страницу. В итоге, в статистике вы наблюдаете якобы случившийся с некоего сайта переход и нулевое время нахождения на странице с 100%-м отказом.

ItSALive - защищает код счётчиков от выполнения спам-ботами. Код счётчика выполняется только в двух случаях: была сдвинута мышка или useragent принадлежит роботам.
