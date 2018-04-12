**Heatconduct** 
1.	Для работы программы необходимо установить последнюю версию Java Runtime Environment. Скачать можно здесь:
http://www.oracle.com/technetwork/java/javase/downloads/2133155
 или https://java.com/ru/download/
2.	После установки Java запустить приложение Heatconduct.jar.
3.	Программа работает с файлами Excel 97-2003 *.xls
4.	Программа берёт данные из первого листа.
5.	Первые две строки на рабочем листе - служебные. В первой строке указываются ключи столбцов:

Ключ | Значение
-----|-------------
`N`|Номер измерения
`DATE`|Дата
`Q_IN`|Тепловой поток через внутреннюю поверхность
`Q_OUT`|Тепловой поток через наружную поверхность
`A_IN`|Коэффициент теплоотдачи внутренней поверхности
`A_OUT`|Коэффициент теплоотдачи наружной поверхности
`T_AIR_IN`|Температура внутреннего воздуха
`T_AIR_OUT`|Температура наружного воздуха
`T1...Т(N)`|Показания датчиков температуры в толще стены. В любом порядке с первого до N-ного.
см. файл sample.xls.

6.	Во второй строке можно подписать столбцы для удобства (никак не влияет на работу программы)
7.	В меню настройки можно загрузить изображение подложку в формате jpg, bmp, png. Рекомендуемый размер изображения подложки - 398х500 пикселей.
