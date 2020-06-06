# 41 - Систем за споделување на слики
Во рамките на овој проект го изработивме системот за споедлување на слики „Imgly“. Фотографите можат да дојдат на Imgly за да откријат и споделат неверојатни фотографии, да добијат значителна изложеност, да се ги категоризираат своите фотографии во албмуми со фотографии и да изберат со кој да ги споделат своите слики.

![Sceenshot од Index страницата на Imgly](http://sites.visionsolutions.mk/imgly/imgly-screenshot.png)

# Изработиле
* Бојан Каркалашев 172002
* Филип Велков 161045

# Технологии
За изработка на проектот се употребени следните технологии/алатки:
* [Bootstrap 4.5.0](https://getbootstrap.com/)
* [JQuery 3.5.1](https://jquery.com/)
* [Popper.js 1.16.0](https://popper.js.org/)
* [Bootstrap Tag Input](https://github.com/Nodws/bootstrap4-tagsinput)
* [Font Awesome 5](https://fontawesome.com/)
* [Google Material Icons](https://material.io/resources/icons/?style=baseline)

# Работна верзија
Веб апликацијата е достапна на следниот линк [http://sites.visionsolutions.mk/imgly](http://sites.visionsolutions.mk/imgly)

# Инсталација
Симнете го проектот на вашиот компјутер со следната команда
`git clone git@github.com:bojankarkalasev/KI_172002_161045.git`
Толку - апликацијата е спремна за работа!

# Извршување
Апликацијата може да ја извршите на два начини:
1. Само кликнете на датотеката `index.html` и апликацијата ќе се отвори во вашиот веб прелистувач.
2. Доколку кориснете веб сервер (Windows, macOS, Linux, Unix околина) само поставете ги сите датотеки на проектот на веб серверот и внесете ја адресата (пр. `localhost/KI_172002_161045`) во вашиот веб прелистувач и апликацијата ќе се отвори.

# Упатство
Јавниот дел е составен од:
* Почетна (Explore) (`index.html`) - Се пристапува преку главната навигација
* Editor's Choice (`editors.html`) - - Се пристапува преку главната навигација
* Sign In (`login.html`) - Се пристапува преку главната навигација
* Reset password (`forgot.html`) - Се пристапува преку копче на страницата `login.html`
* Register (`register.html`) - Се пристапува преку главната навигација
* Тerms (`terms.html`) - Се пристапува преку Footer
* Privacy (`privacy.html`)  - Се пристапува преку Footer
* Contact (`contact.html`) - Се пристапува преку Footer

До Корисничкиот дел се пристапува преку кликање на копчето `Login` на страницата Sign In (`login.html`) и тој е составен од:
* Feed (`user-index.html`)
* Explore (`user-explore.html`)
* Editor's Choice (`user-editors.html`)
* Profile (`user-profile.html`)
* Submit a photo (`user-upload.html`)
