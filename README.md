**#Проєкт тестового завдання створено за допомогою збірника Parcel.**

Сайт адаптовано під мобільні пристрої S, M, L.

**[Посилання на живу сторінку](https://nadiakhoptiuk.github.io/megogo-test-task/)**

Для запуску проєкту локально потрібно склонувати його, встановити залежності
через команду _nmp install_, запустити сервер розробки командою _npm start_ та
відкрити посилання на
[локальний хост http://localhost:1234/](http://localhost:1234/)

**##Технічні особливості:**

У проєкті використано бібліотеку **Swiper** для реалізації поекранного скролу.
Кожен екран займає всю ширину та висоту в'юпорта.

Використовується препроцесор **SASS** та **BEM методологія** найменування
класів. Загальні властивості, схожі між собою, для повторного використання
винесено у _плейсхолдери_ в [файлі](/src/sass/utils/_placeholders.scss) (стилі
заголовків, текстів та кнопок), а також - у класи в
[файлі](/src/sass/base/_common.scss). Для скорочення та полегшення записів
css-властивостей використовуються різноманітні _міксіни_ в
[файлі](/src/sass/utils/_mixins.scss).

Використано _відносні одиниці_ для тексту (**rem**) та для відступів (**vh**).
Від себе я додала _анімацію стрілки_ у першому екрані, також **meta-теги** та
_фавікон_.

Замінила зображення поганої якості в першому екрані на стокове.
