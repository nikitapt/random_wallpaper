# random_wallpaper

Данную программу я написал, чтобы закрепить свои знания в парсинге 23 июня 2022 года. Программа парсит рандомное изображение с сайта https://www.goodfon.ru/
и устанавливает полученное изображение на рабочий стол как обои. Был сделан графический интерфейс с помощью библиотеки pygame.

Интерфейс: Пользователь выбирает тему для обоев, например: настроение, кошки, рендеринг, фантастика или любую другую тему из 34 предложенных вышеупомянутым сайтом.
Программа делает get запросы с помощью модуля requests, и с помощью свойтсва text получает HTML-код страницы, отвечающей за выбранную вами тему.
Далее выбирается рандомное изображение, соответствующее выбранной вами теме, скачивается на ПК и устанавливется на обои.
Если изображение не устраивает пользователя, он может снова выбрать тему картинки и так пока ему не понравится. Также созданы кнопки навигации,
чтобы можно было возвращаться к предыдущим изображениям.

Использованные библиотеки:
1) BeautifullSoup
2) Requests
3) Ctypes
4) OS
5) Pygame
6) Random

P.S. Это не крайняя версия приложения; программа не хранит будет хранить на вашем ПК больше одного изображения,
если вы выбрали тему и вам не понравилось изображение, то предыдущее будет удалено, чтобы не загрязнять память;
на данном этапе существуют баги (Готовая программа будет опубликована до 5 июля года).
