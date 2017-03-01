# parsing-captcha-3
Пример разбора простой капчи (#python #python3 #captcha #PIL #image_processing) 

От репозитория [parsing-captcha-2](https://github.com/gil9red/parsing-captcha-2) отличается другим видом капчи.

Алгоритм такой же как и в [parsing-captcha-2](https://github.com/gil9red/parsing-captcha-2), но немного доработаны и изменены
функции для работы с этими капчами -- у них фон темный, а вот текст светлый.


##### Лог работы: #####
```
C:\Python34\pythonw.exe C:/Users/ipetrash/Desktop/PyScripts/parsing-captcha-3/main.py

"M47" -- examples\1.png
"tM0" -- examples\2.png
"3Yp" -- examples\3.png
"z5g" -- examples\4.png
"LH3" -- examples\5.png
...
"n8Y" -- examples\299.png
"29P" -- examples\300.png
"1C9" -- examples\301.png

Process finished with exit code 0
```

#### Пример работы парсера:
Файл         | Капча | Результат парсинга
------------ | ------------ | ------------
[examples/1.png](examples/1.png) | ![examples/1.png](examples/1.png) | M47
[examples/2.png](examples/2.png) | ![examples/2.png](examples/2.png) | tM0
[examples/3.png](examples/3.png) | ![examples/3.png](examples/3.png) | 3Yp
[examples/4.png](examples/4.png) | ![examples/4.png](examples/4.png) | z5g
[examples/5.png](examples/5.png) | ![examples/5.png](examples/5.png) | LH3
[examples/6.png](examples/6.png) | ![examples/6.png](examples/6.png) | i7F
[examples/7.png](examples/7.png) | ![examples/7.png](examples/7.png) | h70
[examples/8.png](examples/8.png) | ![examples/8.png](examples/8.png) | wx5
[examples/9.png](examples/9.png) | ![examples/9.png](examples/9.png) | nE4
[examples/10.png](examples/10.png) | ![examples/10.png](examples/10.png) | 25m
