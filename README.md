
> # Тестовое задание dr.Web :crossed_fingers: 
> [Cсылка](https://github.com/1deam0nster/dr_web_test/deployments/github-pages) на выполненное тестовое задание.





 
Добрый день меня зовут Дмитрий Реута, я занимаюсь web разработкой, программированием и UX/UI дизайном.

* 🌍  Я живу в ближайшем подмосковье, г.Ногинск
* 📃  Скачать резюме в формате pdf: [Веб разработчик](https://hh.ru/resume_converter/%D0%A0%D0%B5%D1%83%D1%82%D0%B0%20%D0%94%D0%BC%D0%B8%D1%82%D1%80%D0%B8%D0%B9%20%D0%A1%D0%B5%D1%80%D0%B3%D0%B5%D0%B5%D0%B2%D0%B8%D1%87.pdf?hash=b8b8fab8ff0c5d000f0039ed1f63546e543070&type=pdf&hhtmSource=resume&hhtmFrom=resume_list)
* 🖥️  Мое портфолио(ux/ui): [reut.online](http://reut.online)
* ✉️  Связатся со мной: [reutadm@gmail.com](mailto:reutadm@gmail.com)
* 🧠  Программирую/проектирую устройства на основе микроконтроллеров esp32/atmel, linux devboards в свободное время. 

* 🤝  Открыт для сотрудничества в интересных проектах 



[![My Skills](https://skillicons.dev/icons?i=js,html,css,sass,nodejs,npm,webpack,yarn,tailwind,vue,astro,bootstrap,python,flask,docker,webflow,ps,figma,vscode,linux,debian,cpp,arduino,raspberry)](https://skillicons.dev)

---

## Небольшое сопроводительное письмо

- К сожаление, я немного не внимательно прочитал задание, подумал что запрещается использовать любые CSS препроцессоры и постобработку. Поэтому сделал на чистом CSS, tсли что могу переделать, например на Tailwand css.

- Верстку сделал **mobile first**, посторался выполнить по-принципу **pixel perfect**(накладывал скриншоты макета поверх страницы браузера). Так как макет все-таки тестовый, собран он на скорую руку, в нем множество ошибок из-за которых получить Pixel Perfect верстку не возможно. Например: очень много значений с точкой *(height: 17.3px)*, не соответствие сетки *(на макете 1920 второй блок с карточкой товара уже остальных, единообразие не прослеживается) или например в макете на 480px в этом же блоке растянут фон, разные скругления углов на всех макетах. 
*Поэтому прошу не сильно обращать внимание на чистоту/красоту разметки.*

- В итоге, есть много моментов которые можно улучшить, ускорить загрузку, упростить дальнейшую поддрежку, но про это не было сказанно в ТЗ.

![Mobile-480px](https://caferecer.ru/1.gif)


***

# Задача

Сверстать лендинг по макету из Figma: **[Макет](https://www.figma.com/file/ZbO9i7y6g8YJWSwNkodFgm/Dr.Web_Frontend_Test?type=design&node-id=0%3A1&mode=design&t=wEPlADWGrT62oYul-1)**, **[Прототип](https://www.figma.com/proto/ZbO9i7y6g8YJWSwNkodFgm/Dr.Web_Frontend_Test?page-id=0%3A1&type=design&node-id=2-1246&viewport=577%2C736%2C0.36&t=CdgMZpnx7hE17f6i-1&scaling=scale-down-width&starting-point-node-id=2%3A1246&mode=design)**

### Поведение элементов:

**1 экран:** кнопка “Купить со скидкой” якорит на экран с продуктовым блоком. 

**2 экран:** “Условия акции” ссылка на страницу. 


## Метаданные страницы:

**Title** 
Скидка 20% на Dr.Web Security Space (для Android)

**Description**
С 1 по 15 февраля 2024 года скидка 20% на Dr.Web Security Space для Android, 2 устройства на 1 год всего за 784 руб.

**Keywords** 
dr.web promo, dr.web android


### Технологии
- Приветствуется mobile-first вёрстка. 
- JS (без jQuery и других библиотек / фреймворков, упрощающих и дополняющих функциональность окружения браузера).
- CSS или любые другие пре/постпроцессоры.
- HTML (без использования шаблонизаторов).
