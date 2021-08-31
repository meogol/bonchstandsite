<script>
let k = 0;
function viewMediaInfo(){
    k= k+1;
    if(k==1){
    document.getElementById("mediaInfo").style.display="block";
    }
    else{
        k=0;
        document.getElementById("mediaInfo").style.display="none";
    }
}

let k1 = 0;
function viewRadioInfo(){
    k1= k1+1;
    if(k1==1){
        document.getElementById("radioInfo").style.display="block";
    }
    else{
        k1=0;
        document.getElementById("radioInfo").style.display="none";
    }
}
</script>


<div class="qst">
    <p> Где занимаются наши студенты?</p>
</div>

<div class="mediacenter">
    <div id="textContainerMedia">
        <h1 id="mediaHeader">НОЦ <br> "Медиацентр"</h1>
        <p id="mediaTextUnderHeader">Освоение<br>технологий<br>радиовещания </p>
        <button class="PressMe" on:click={viewMediaInfo}>Подробнее</button>
    </div>
    <img class="photo-media" src="images/mediacenter.png" alt="Изображение камеры">

</div>
<div class="mediaInfoHolder">
    <p id="mediaInfo">
Научно-образовательный центр «Медиацентр» СпбГУТ — это уникальное
объединение медиаспециалистов и студентов, которое с каждым годом
развивается и достигает новых целей. Особым успехом коллектива стало
объединение множества вузов России в результате начатого университетом
проекта «Всероссийский студенческий медиапортал».
«Медиацентр» обеспечен самым современным и передовым оборудованием.
Профессиональная техника предоставляет широкие возможности учащимся в
освоении технологий телерадиовещания, а специалисты, работающие здесь,
помогают студентам раскрыть свой творческий потенциал.<br>
В состав Медиацентра СПбГУТ входят:<br>
•телевизионная студия;<br>
•фотостудия;<br>
•монтажная аппаратная;<br>
•студия звукозаписи;<br>
•радиостудия «Радио Бонч»;<br>
•учебно-исследовательская лаборатория.<br>
На базе Медиацентра осуществляются следующие проек&shy;ты:<br>
• Радио «Бонч»,<br>
• Bonch|News,<br>
• Всероссийский студенческий медиапортал,<br>
• Виртуальный тур.<br>
НОЦ «Медиацентр» является площадкой для популяризации науки не только
среди сотрудников, но и среди студентов. Здесь проходят мастер-классы,
факультативы, курсы повышения квалификации. Ведется работа над
студенческим проектом «БончНаучФильм», в рамках которого студенты
снимают научно-популярные фильмы.Учебные занятия, которые проводятся в
НОЦ «Медиацентр» кафедрами ТВиМ и РСиВ, раскрывают современные
аспекты медиатехнологий, в частности технологии виртуальной и дополненной
реальности, особенности 3D видео и видео 360°.
Сотрудники НОЦ «Медиацентр» проводят съемки всех значимых событий в
СПбГУТ — научных конференций, семинаров, лекций, форумов, а также
студенческих мероприятий — «Кубок ректора», «Мисс и мистер СПбГУТ» и т.
п.<br>
Группа видеотехнологий<br>
Большую часть времени отдела занимает работа со студентами. Раз в полгода
НОЦ «Медиацентр» проводит кастинг в студенческий проект BonchNews Team,
и студенты, прошедшие отбор, становятся операторами, корреспондентами и
ведущими YouTube-канала. Также на базе видеоотдела работает и фотостудия,
где сотрудники НОЦа рассказывают как правильно работать с камерой для
получения отличной фотографии.<br>
Группа аудиотехнологий<br>
Самый значимый проект отдела — студенческое радио СпбГУТ «Радио Бонч».
Над ним работают и сотрудники НОЦ «Медиацентр», и студенты. Попасть на
радио может любой студент, достаточно пройти кастинг, который также
проводится раз в полгода. Студенты могут представить себя на месте
профессиональных ведущих, узнать тонкости работы с пультом и
микрофонами, научиться работать в команде.<br>
В аудиоотделе НОЦ Медиацентр существует и студия звукозаписи. Она
предназначена для записи музыкальных коллективов, вокалистов, реставрации
фонограмм, написания музыки, озвучания кинофильмов. Также проводятся
записи закадрового текста для видеосюжетов. Медиацентр приглашает
студентов попробовать свои силы, получить опыт работы с аудио- и
видеоаппаратурой, реализовать собственные проекты.<br>
Ссылка на ютюб - <a href="https://www.youtube.com/channel/UCmHH-0sF7oH4iLF-oxtbdzg">https://www.youtube.com/channel/UCmHH-0sF7oH4iLF-oxtbdzg</a> <br>
-||- радио бонч - <a href="https://www.sut.ru/radio">https://www.sut.ru/radio</a> <br>
-||- бонч news - <a href="https://www.sut.ru/media/Bonch-News">https://www.sut.ru/media/Bonch-News</a> <br>
-||- всероссийский студенческий медиапортал — <a href="http://медиапортал.рф/">http://медиапортал.рф/</a> <br>
-||- виртуальный тур - <a href="https://www.sut.ru/media/virtualniy-tur">https://www.sut.ru/media/virtualniy-tur</a> <br>
    </p>
</div>

<hr color="#EBEDF0" class="spacer">

<div class="radio">
    <div id="textContainerRadio">
        <h1 id="radioHeader">НИЛ <br> "РЭС"</h1>
        <p id="radioTextUnderHeader">Радиоконтроль<br>Разработки<br>Исследования </p>
        <button class="PressMe" on:click={viewRadioInfo}>Подробнее</button>
    </div>
    <img class="photo-radio" src="images/radiobonch.jpg" alt="Радио СПбГУТ">
</div>
<div class="radioInfoHolder">
    <p id="radioInfo">
        Научно-исследовательская лаборатория радиоконтроля и электромагнитной
        совместимости<br>
        Лаборатория проводит:<br>
        •научно-исследовательские работы, ориентированные на решение
        концептуальных задач создания и развития системы радиоконтроля и
        управления использованием спектра;<br>
        •проектирование и разработку радиоконтрольного оборудования в
        соответствии с требованиями МСЭ (международный союз электросвязи);<br>
        •обучение и переподготовку специалистов радиочастотной службы,
        госсвязьнадзора и других заинтересованных организаций.
        Исследования и Разработки<br>
        Результаты теоретических исследований, проводимых в лаборатории
        воплощаются в жизнь в новых продуктах: измерительных комплексах,
        аппаратуре, антеннах, программном обеспечении.<br>
        Особое внимание уделяется методическому обеспечению измерений. В стенах
        лаборатории разработан ряд методик проведения измерений параметров
        радиоизлучений по электромагнитному полю. Сотрудники лаборатории
        публикуют результаты исследований в авторитетных научных изданиях, ряд
        разработок лаборатории использованы в рекомендациях Международного
        Союза Электросвязи.<br>
        Обучение<br>
        Лаборатория активно участвует в подготовке высококвалифицированного
        персонала для радиочастотных и надзорных органов. Регулярно проводятся
        семинары повышения квалификации и переподготовки. Лаборатория
        периодически участвует в организации и проведении региональных,
        межрегиональных и международных конференций и семинаров посвященных
        различным аспектам радиоконтроля, связи, измерений.<br>

    </p>
</div>

<style>
    .qst{
        font-size: 10px;
        margin-left: 65%;

    }

    .mediacenter{
        background-color: white;
        display: -webkit-flex;
        display: -ms-flex;
        display: flex;
        align-items: center;
        max-width: 80%;
        margin-left: 10%;
    }
    .photo-media{
        margin-left: auto;
        margin-right: 5px;
        margin-bottom: 5px;
        margin-top: 5px;
        border-radius: 10px;
    }
    #mediaHeader{
        font-size: 3vw;
        font-family: Gilroy;
        margin-bottom: auto;
        margin-left: 5px;
    }
    #mediaTextUnderHeader{
        font-size: 2.5vw;
        display: block;
        margin-left: 5px;
    }
    #textContainerMedia{
        display: block;
        margin-left: 10px;
    }
    .mediaInfoHolder{
        display: flex;
        max-width: 100%;
    }
    #mediaInfo{
        display: none;
        margin:10px;
        font-size: 3.5vw;
        word-break: break-all;
    }
    .PressMe{
        margin-left: 7px;
        max-width: 100%;
        background-color: rgba(255, 169, 39, 0.99);
        color: white;
        border-radius: 5px;
        font-size: 3vw;
        text-shadow: #333333;
    }
    .radio{
        background-color: white;
        display: -webkit-flex;
        display: -ms-flex;
        display: flex;
        align-items: center;
        max-width: 80%;
        margin-left: 10%;
    }

    .photo-radio{
        margin-left: auto;
        margin-right: 5px;
        margin-bottom: 5px;
        margin-top: 5px;
        border-radius: 10px;
        height: auto;
        width: 100%;
        max-width: 180px;

    }
    #radioHeader{
        font-size: 2.6vw;
        margin-bottom: auto;
        margin-left: 5px;
    }
    #radioTextUnderHeader{
        font-size: 2.5vw;
        display: block;
        margin-left: 5px;
    }
    #textContainerRadio{
        display: block;
        margin-left: 10px;
    }
    .spacer{
        padding: 15px;
    }
    .radioInfoHolder{
        display: flex;
        max-width: 100%;
    }
    #radioInfo{
        display: none;
        margin:10px;
        font-size: 3.5vw;
        word-break: break-all;
    }
</style>