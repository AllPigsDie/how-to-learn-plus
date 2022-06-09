блок video:
Видео нa TED
Для тех, кто любит прокрастинировать


___________________________
блок oakley:
История Барбары Оакли.
С детства Барбаре не давалась математика. Она считала себя законченным гуманитарием, причём далеко не самым умным. В армии она изучала русский язык, чтобы получить надбавку, да так успешно, что её выдвинули в командиры. Но для продвижения по службе нужно было сдавать математику. И тогда Барбара придумала свой подход к точным наукам. Оказалось, если вам что-то «плохо даётся», ваши добытые трудом знания гораздо глубже, чем у тех, кому всё ясно с первого взгляда.


___________________________
блок feynman:
Метод Фейнмана
Выучить и не забыть.

background: url('./images/feynman.png') bottom left/867px 637px no-repeat;
___________________________
блок khan:
Салман Хан
Весь мир — школа

Страсть и новаторство Сала Хана меняют процесс обучения миллионов студентов по всему миру. Книгу «Весь мир — школа» нужно прочитать всем, кто занимается образованием — так учащиеся повсюду смогут получить навыки и знания, которые приносят успех в школе, карьере и жизни.

Джордж Лукас
Кинорежиссер, продюсер

___________________________
html,
body {
  margin: 0;
  padding: 0;
}

@keyframes square {
  from {
    transform: rotate(0deg);
  }
  to {
    transform: rotate(360deg);
  }
}

.page {
  min-width: 1100px;
  max-width: 1600px;
  margin: 0 auto;
  font-family: "Helvetica Neue", Arial, sans-serif;
}
.logo {
  height: 32px;
  width: 228px;
}

.logo_place_header {
  position: absolute;
  left: 64px;
  top: 30px;
  background-image: url("./images/logo_place_header.svg");
}

.header {
  height: 100vh;
  min-height: 600px;
  max-height: 756px;
  background-color: #f2f2f2;
  display: flex;
  align-items: center;
  position: relative;
  overflow: hidden;
}

.header__title {
  width: 730px;
  margin-left: 64px;
  line-height: 96px;
  font-size: 102px;
  font-weight: bold;
}

.header__subtitle {
  width: 388px;
  line-height: 25px;
  font-size: 18px;
  font-weight: normal;
  position: absolute;
  bottom: 30px;
  left: 84px;
}


.header__square-pic {
  height: 568px;
  width: 568px;
  background-color: #2f80ed;
  position: absolute;
  bottom: 0;
  right: 0;
  top: 64px;
  animation: square 20s linear infinite;
}

.header__main-illustration {
  width: 765px;
  height: 608px;
  position: absolute;
  bottom: 0;
  right: 0;
}

.description {
  display: flex;
  padding-top: 100px;
}

.two-columns {
  width: 80%;
  margin: auto;
  display: flex;
  justify-content: space-between;
  align-items: flex-start;
}

.two-columns__brief {
  width: 175px;
  line-height: 1.2;
  font-size: 18px;
  font-weight: normal;
  color: #2f80ed;
  margin: 0;
}

.two-columns__main-text {
  width: 80%;
  min-width: 784px;
  display: flex;
  flex-direction: column;
  gap: 30px;
}

.two-columns__main-text_paragraf {
  line-height: 34px;
  font-size: 24px;
  font-weight: normal;
  margin: 0;
}

.two-columns__span-accent {
  line-height: 34px;
  font-size: 24px;
  font-weight: bold;
}

.techniques {
  width: 80%;
  margin: auto;
  padding-top: 100px;
}

.section-title {
  width: 60%;
  margin: auto;
  margin-bottom: 20px;
  text-align: center;
  line-height: 1.15;
  font-size: 60px;
  font-weight: bold;
}

.section-subtitle {
  width: 60%;
  margin: auto;
  text-align: center;
  line-height: 34px;
  font-size: 24px;
  font-weight: normal;
}

.cards {
  width: 920px;
  margin: 0 auto;
  display: flex;
  flex-wrap: wrap;
  column-gap: 100px;
}

.cards__item {
  width: 240px;
}

.cards__item_image {
  width: 160px;
  height: 160px;
  border-radius: 50%;
  margin: 60px 40px 43px 40px;
}

.cards__title {
  text-align: center;
  line-height: 1.15;
  font-size: 24px;
  font-weight: bold;
  margin: 0;
}

.cards__description {
  line-height: 23px;
  font-size: 18px;
  font-weight: normal;
  text-align: center;
  margin-bottom: 0;
  margin-top: 16px;
}
.video {
  padding-top: 100px;
}

.video__iframes {
  width: 1050px;
  margin-left: auto;
  margin-right: auto;
  display: flex;
  justify-content: space-between;
  position: relative;
  top: 50px;
}

.video__iframe {
  width: 515px;
  height: 316px;
}

.oakley {
  padding-top: 160px;

  background-color: #f2f2f2;
}

.feynman {
  height: 890px;
  padding-top: 100px;
  background: url("./images/feynman.png") bottom left/867px 637px no-repeat;
  position: relative;
  background-color: #f2f2f2;
}

.feynman__title {
  line-height: 1.15;
  font-size: 120px;
  font-weight: bold;
  width: 648px;
  margin: auto;
  margin-top: 100px;
  text-align: center;
}

.feynman__subtitle {
  line-height: 51px;
  font-size: 36px;
  font-weight: normal;
  text-align: center;
  margin-top: 70px;
}

.feynman__link {
  line-height: 51px;
  font-size: 36px;
  font-weight: normal;
  position: absolute;
  top: 445px;
  right: 48px;
}

.digits {
  padding-top: 100px;
}

.table {
  width: 1100px;
  margin: auto;
  padding: 0;
  list-style: none;
  display: flex;
  flex-wrap: wrap;
  justify-content: space-between;
}

.table__cell {
  width: 250px;
  flex-direction: column;
  list-style-type: none;
  padding: 0;
  margin: 60px 0 0;
}

.table__heading {
  line-height: 1.15;
  font-size: 24px;
  font-weight: bold;
}

.table__text {
  line-height: 1.2;
  font-size: 18px;
  font-weight: normal;
  margin-top: 20px;
  margin-bottom: 0;
}
.khan {
  padding-top: 100px;
  background-color: #f2f2f2;
}

.khan__container {
  width: 80%;
  margin: auto;
}

.khan__author {
  line-height: 42px;
  font-size: 30px;
  font-weight: normal;
  margin: 0;
  padding: 0;
}

.khan__title {
  line-height: 1.15;
  font-size: 60px;
  font-weight: bold;
  margin: 0;
  padding: 0;
}

.khan__quote {
  line-height: 34px;
  font-size: 24px;
  font-weight: normal;
  width: 790px;
  margin-top: 50px;
  margin-bottom: 36px;
}

.khan__quote-author {
  line-height: 1.15;
  font-size: 24px;
  font-weight: bold;
  margin: 0;
}

.khan__quote-author-subline {
  line-height: 1.15;
  font-size: 24px;
  font-weight: normal;
  margin-top: 10px;
  margin-bottom: 68px;
}

.khan__book-container {
  display: flex;
}

.khan__book-pic {
  width: 620px;
  height: 608px;
  margin-right: 48px;
  object-fit: cover;
  object-position: top;
}
.khan__buy-link {
  line-height: 42px;
  font-size: 30px;
  font-weight: normal;
  text-decoration: none;
}

.kaufman {
  padding-bottom: 90px;
  padding-top: 90px;
  overflow: hidden;
  position: relative;
  z-index: 0;
  background-color: #1f1f1f;
}
.section-title_theme_dark {
  color: white;
}

.section-subtitle_theme_dark {
  color: white;
}

/* и элемента с модификатором вида ключ-значение */
.table__cell_theme_dark {
  width: 200px;
  color: white;
  margin-right: 0;
  margin-top: 80px;
  padding: 0;
}

.table__heading_theme_dark {
  color: white;
}

.table__text_theme_dark {
  margin-bottom: 0;
  color: white;
}

.kaufman__triangle {
  width: 877px;
  height: 877px;
  position: absolute;
  top: 0;
  right: -210px;
  z-index: -1;
  background-repeat: no-repeat;
  animation: square 20s linear infinite;
}

.resources {
  padding-top: 100px;
}

.resources__logo-zone {
  width: 1100px;
  margin: auto;
  margin-top: 80px;
  margin-bottom: 217px;
  display: flex;
}

.resources__link {
  height: 38px;
  width: 270px;
  display: flex;
  justify-content: center;
  flex-grow: 1;
}

.footer {
  min-height: 350px;
  display: flex;
  box-sizing: border-box;
  background-color: #1f1f1f;
}

.footer__columns {
  width: 90%;
  margin-top: 60px;
  margin-bottom: 40px;
  margin-left: auto;
  margin-right: auto;
  display: flex;
  justify-content: space-between;
}

.footer__column_content_copyright {
  display: flex;
  flex-basis: 711px;
  flex-direction: column;
  justify-content: space-between;
}

.logo_place_footer {
  background-image: url("./images/logo_place_footer.svg");
}

.footer__author {
  margin-top: 18px;
  margin-bottom: 18px;
  line-height: 25px;
  font-size: 18px;
  font-weight: normal;
  color: white;
}

.footer__column-heading {
  margin-top: 0;
  line-height: 18px;
  font-size: 18px;
  font-weight: bold;
  color: white;
}

.footer__column-links {
  list-style: none;
  padding: 0;
  display: flex;
  flex-direction: column;
  margin-bottom: 16px;
  margin-top: 20px;
  gap: 10px;
}

.footer__column-link {
  text-decoration: none;
  line-height: 18px;
  font-size: 18px;
  font-weight: normal;
  color: white;
}

.footer__social-icon {
  width: 16px;
  height: 16px;
}
