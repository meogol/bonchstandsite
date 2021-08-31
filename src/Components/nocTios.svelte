<script>
    let k = 0;
    function viewInfo(){
        k= k+1;
        if(k==1){
            document.getElementById("tiosInfoHolderID").style.display="block";
            document.getElementById("tiosInfo").style.display="flex";

            document.getElementById("ssilka").style.display="block";
            document.getElementById("btnIntiosInfoHolder").style.display="block";
        }
        else{
            k=0;
            document.getElementsByClassName("tiosInfoHolder").display="none";
            document.getElementById("tiosInfo").style.display="none";
            document.getElementById("machinesHolderID").style.display="none";
            document.getElementById("ssilka").style.display="none";
            document.getElementById("btnIntiosInfoHolder").style.display="none";
            k1 = 0;

        }
    }
    let k1 = 0;
    function viewMachines(){
        k1=k1+1;
        if(k1==1){
            document.getElementById("machinesHolderID").style.display="block";

        }
        else {
            k1=0;
            document.getElementById("machinesHolderID").style.display="none";
        }
    }
</script>
<div class="Tios">
    <div id="textContainerTios">
        <h1 id="Tios">НОЦ <br> "ТИОС"</h1>
        <p id="TiosTextUnderHeader">Воплоти<br>в жизнь <br>свои идеи </p>
        <button class="PressMe" on:click={viewInfo}>Подробнее</button>
    </div>
    <img class="photo-Tios" src="images/Tios.jpg" alt="Технологии информационных
образовательных систем">
</div>
<div class="tiosInfoHolder" id="tiosInfoHolderID">
    <p id="tiosInfo">
        Научно-образовательный центр "Технологии информационных
        образовательных систем" (НОЦ ТИОС) при СПбГУТ.<br>
        В НОЦ "ТИОС" вам предоставляется возможность воплотить в жизнь свои идеи
        в сфере радиоэлектроники от электронной начинки до уникального дизайна
        корпуса.<br>
        Зачем студентам приходить в ТИОС:<br>
        · Прокачка скилов в выбраной сфере деятельности;<br>
        · Приобретение навыков работы с реальными проектами или оборудованием;<br>
        · Проведение времени в университете с единомышленниками или друзьями с
        интересом и пользой для себя.<br>
        Оборудование и возможности.<br>
        Производственный сектор:<br>
        1. 3D принтер, предназначенный для печати трёхмерных моделей высокого
        качества из пластика.<br>
        2. Лазерный станок с ЧПУ — предназначен для выполнения задач по лазерной
        резке и гравировке.<br>
        3. Настольный токарный станок для механической обработки изделий из
        металлов, древесины и пластмасс.<br>
        4. Ультрафиолетовый принтер для печати на твердых и гибких носителях
        методом ультрафиолетовой печати.<br>
        5. Фрезерный настольный станок для выполнения операций фрезерования
        различных деталей из черных и цветных металлов и их сплавов в условиях
        серийного и мелкосерийного производства.<br>
        6. DIY-принтер для самостоятельной сборки из поставляемых в комплекте
        блоков и деталей.<br>
        Приемные усторойства:<br>
        1. Ettus USRP — универсальное приёмо-передающее устройство для
        разработки SDR (Software defined radio) систем.<br>
        2. National Instruments myRIO — программно-аппаратная платформа,
        которая нацелена на предоставление студентам инженерам возможность
        быстро разрабатывать реальные системы для автоматизации,
        робототехники, регистрации данных и встроенных систем.<br>
        3. DRM Modulator LV Series. Семейство модуляторов DRM использует
        доставляемый MDI радиоконтент для получения модулированного и/или
        преобразованного ВЧ радиосигнала и так далее.<br>
        Разработка электроники:<br>
        1. Raspberry PI 3 — одноплатный компьютер размером с банковскую карту,
        позволяющий выполнять многие функции, доступные мощным
        настольным системам.<br>
        2. Cyclone IV – программируемая логическая интегральная схема (ПЛИС).<br>
        3. Arduino NANO — компактная платформа для прототипирования
        микроэлектронных устройств, предназначенная для использования с
        макетной платой и многое другое.<br>
        Факультативы.<br>
        I. 3D MAX моделирование.<br>
        В текущее время большое внимание уделяется к дизайну в проектировании
        объектов. Факультатив «Методы креативного моделирования трёхмерных
        объектов в полигональной программе «3DS MAX» является совершенно новым
        подходом в работе с трёхмерным пространством для учащихся. Направлен на
        развитие креативного подхода и мышления, понимания и представления
        объектов в трёхмерной среде.<br>
        Цели и задачи факультатива:<br>
        1. Научить студентов моделированию объектов и подготовке объектов к 3D
        печати или созданию прототипа на ЧПУ станке.<br>
        2. Подобрать для каждого свой способ, метод и видение в трёхмерном
        моделировании.<br>
        3. Освоить новые перспективных и необычные подходов к созданию любых
        объектов в пространстве, или даже создания виртуального мира или
        вселенной.<br>
        II. Основы устройства, программирования и пилотирования квадрокоптеров.
        Факультатив «Основы устройства, программирования и пилотирования
        квадрокоптеров» позволяет ознакомится с пониманием и устройством работы
        «квадрокоптеров» (дронов). В ходе обучения на факультативе студенты
        получают знания основ аэродинамики, создания и устройств беспилотных
        летательных аппаратов, учатся пилотированию и программированию
        квадрокоптеров. Основным квадрокоптером на базе которого происходит
        обучение в рамках факультатива является квадрокоптер «Геоскан Пионер».
        Цели и задачи факультатива:<br>
        1. Изучить основы робототехники и авионики, а также ознакомиться с
        устройством и принципом работы квадрокоптера.<br>
        2. Освоить приёмы пилотирования и возможности адаптации квадрокоптера
        для решения поставленных задач.<br>
        3. Научиться программировать квадрокоптер для выполнения автономных
        полётов.<br>
        Группа Вконтакте:<br>
    </p>
    <a href="https://vk.com/bonchtios" id="ssilka">https://vk.com/bonchtios</a><br>
    <button id="btnIntiosInfoHolder" class="PressMe" on:click={viewMachines}>Оборудование</button>
</div>
<div class="machinesHolder" id="machinesHolderID">
    <p id="3dPrinterText">
        Picasso Designer PRO250 – 3D принтер предназначенный для печати трёхмерных моделей высокого качества из пластика.<br>
        Размер печатной модели до 20х20х21 см.<br>

        Подробную информацию можно посмотреть <a href="https://drive.google.com/open?id=1eMssqVENbApr_vEmysRZUPvuNdkk8S7A">Здесь</a>.<br>
    </p>
    <img src="images/3dprinter.jpg" class="machineryPics" alt="Изображение 3д принтера">


    <hr color="#EBEDF0" class="spacerSmall">


    <p id="laser">
        Лазерный станок с ЧПУ — предназначен для выполнения задач по лазерной резке и гравировке следующих материалов: фанера, дерево, пластмасса, ткань, кожа, стекло и т.п.<br>
        Подробную информацию можно посмотреть <a href="https://drive.google.com/drive/folders/1wpFOWS_jedForJX-TLbNynoh1elwiMx5">Здесь.</a><br>
    </p>
    <img src="images/laser.jpg" class="machineryPics" alt="Изображение лазерного станка с ЧПУ">


    <hr color="#EBEDF0" class="spacerSmall">


    <p id="tokar">
        Настольный токарный станок QUANTUM D210x400 Vario — предназначен для механической обработки изделий из металлов, древесины и пластмасс.<br>
        Подробную информацию можно посмотреть <a href="https://drive.google.com/open?id=14ZTXWgw13i99vth_S0mZrzAI2a4OeBWz">Здесь.</a><br>
    </p>
    <img src="images/tokar.jpg" class="machineryPics" alt="Изображение токарного станка">


    <hr color="#EBEDF0" class="spacerSmall">


    <p id="ultrafio">
        Mimaki UJF-3042fx — ультрафиолетовый принтер предназначенный для печати на твердых и гибких носителях методом ультрафиолетовой печати. Особенностью УФ печати является стойкость к износу.<br>
        Подробную информацию можно посмотреть <a href="https://drive.google.com/open?id=1r0hyj6AWRPjbGIxUI3fTXrwTLWBtZjgX">Здесь.</a><br>
    </p>
    <img src="images/ultrafio.jpg" class="machineryPics" alt="ультрафиолетовый принтер">


    <hr color="#EBEDF0" class="spacerSmall">


    <p id="diyprinter">
        CREALITY Ender 3 Pro — DIY-принтер для самостоятельной сборки из поставляемых в комплекте блоков и деталей. Конструктивно CREALITY Ender 3 Pro является типичным FDM-принтером открытого типа.<br>
        Экструдер перемещается в двух плоскостях (X и Z). Стол передвигается по оси Y. <br>
        Для загрузки файлов можно использовать прямое соединение с компьютером через USB-кабель, либо загрузить файлы с SD-карты.<br>
        Для выполнения действий принтер оснащен небольшим монохромным дисплеем. Перемещение по меню и выбор пункта осуществляется поворотно-нажимной ручкой. <br>
        Размер рабочей камеры 220х220х250 мм.<br>
        Подробную информацию можно посмотреть <a href="https://yadi.sk/i/PXTAXsKMvKiSrQ">Здесь.</a><br>
    </p>
    <img src="images/diyprinter.jpg" class="machineryPics" alt="Самодельный 3д принтер">


    <hr color="#EBEDF0" class="spacerSmall">


    <p id="raspberry">
        Raspberry PI 3 — одноплатный компьютер размером с банковскую карту, позволяющий выполнять многие функции, доступные мощным настольным системам.  <br>
        Выполняет все функции обычного компьютера. <br>
        Обладает большими графическими возможностямиЮ позволяющими использовать его как платформу для практически любых радиотехнических систем, например, измерительных и робототехнических систем, применяя датчики и исполнительные механизмы.<br>
    </p>
    <img src="images/raspberry.jpg" class="machineryPics" alt="Плата распберри пай">


    <hr color="#EBEDF0" class="spacerSmall">


    <p id="cyclon">
        Cyclone IV – программируемая логическая интегральная схема (ПЛИС). <br>
        Отличается низкой стоимостью логического элемента и самым низким энергопотреблением. <br>
        Кроме трансиверов микросхемы содержат аппаратные умножители, блоки встроенного ОЗУ и аппаратные IP-блоки контроллеров PCI Express.<br>
    </p>
    <img src="images/cyclon.jpg" class="machineryPics" alt="Программируемая логическая интегральная схема">


    <hr color="#EBEDF0" class="spacerSmall">


    <p id="generator">
        Универсальный генератор сигналов Rigol DG1022 — это двухканальный генератор сигналов произвольной формы с формированием сигнала методом прямого синтеза (DDS), который обеспечивает стабильный, высокоточный, чистый синусоидальный сигнал с низким уровнем искажений. <br>
        100 милионов выборок в секунду с разрешением по вертикали 14 бит и глубиной памяти 4Кб позволяют генератору формировать идеально точный и стабильный сигнал. <br>
        Генератор сигналов Rigol DG1022 может также выдавать прямоугольной формы сигнал с частотой 5МГц с идеальными передними и задними фронтами. <br>
        Генератор сигналов произвольной формы Rigol DG1022 имеет простую и удобную в использовании переднюю панель управления.<br>

    </p>
    <img src="images/generator.jpg" class="machineryPics" alt="Универсальный генератор сигналов">


    <hr color="#EBEDF0" class="spacerSmall">


    <p id="hacker">
        HackRF One от Ggreate Scott Gadgets — устройство программно-конфигурируемого радио способное передавать или принимать радио-сигналы на частотах от 1 МГц до 6 ГГц. <br>
        Созданная для тестирования и разработки современных и будущих (next-gen) радио-технологий, HackRF One является открытой аппаратной платформой, которая может быть использована как USB периферийное устройство или же запрограммировано на автономную работу.<br>
    </p>
    <img src="images/hacker.jpg" class="machineryPics" alt="устройство программно-конфигурируемого радио">


    <hr color="#EBEDF0" class="spacerSmall">


    <p id="platform">
        National Instruments myRIO — программно-аппаратная платформа, которая нацелена на предоставление студентам инженерам возможность быстро разрабатывать реальные системы для автоматизации, робототехники, регистрации данных и встроенных систем. <br>
        Аппаратное обеспечение основано на Xilinx Zynq-7010 с двухъядерным процессором ARM Cortex-A9 и FPGA с 28000 программируемых логических ячеек, а также имеет 10 аналоговых входов, 6 аналоговых выходов, аудио каналы ввода / вывода, а также до 40 линий цифрового ввода / вывода (DIO).<br>
    </p>
    <img src="images/platform.jpg" class="machineryPics" alt="программно-аппаратная платформа">


</div>
<style>
    .Tios{
        background-color: white;
        display: -webkit-flex;
        display: -ms-flex;
        display: flex;
        align-items: center;
        max-width: 80%;
        margin-left: 10%;
    }
    .photo-Tios{
        margin-left: auto;
        margin-right: 5px;
        margin-bottom: 5px;
        margin-top: 5px;
        border-radius: 10px;
        height: auto;
        width: 100%;
        max-width: 180px;
    }
    #Tios{
        font-size: 3vw;
        font-family: Gilroy;
        margin-bottom: auto;
        margin-left: 5px;
    }
    #TiosTextUnderHeader{
        font-size: 2.5vw;
        display: block;
        margin-left: 5px;
    }
    #textContainerTios{
        display: block;
        margin-left: 10px;
    }
    .PressMe{
        margin-left: 7px;
        margin-top: 5px;
        max-width: 100%;
        background-color: rgba(255, 169, 39, 0.99);
        color: white;
        border-radius: 5px;
        font-size: 3vw;
        text-shadow: #333333;
    }
    .tiosInfoHolder{
        max-width: 100%;
    }
    #tiosInfo{
        display: none;
        margin:10px;
        font-size: 3.5vw;
        word-break: break-all;
    }
    #tiosInfoHolderID{
        display: none;
    }
    #3dPrinterText{
        margin:10px;
        font-size: 3.5vw;
        word-break: break-all;
    }
    .machineryPics{
        margin: auto;
        border-radius: 10px;
        height: auto;
        width: 100%;
    }
    #machinesHolderID{
        display: none;
    }
    #ssilka{
        margin-left: 10px;
    }
    #btnIntiosInfoHolder{

    }
    .spacerSmall{
        padding: 20px;
    }
    #laser{
        margin:10px;
        font-size: 3.5vw;
        word-break: break-all;
    }
    #tokar{
        margin:10px;
        font-size: 3.5vw;
        word-break: break-all;
    }
    #ultrafio{
        margin:10px;
        font-size: 3.5vw;
        word-break: break-all;
    }
    #diyprinter{
        margin:10px;
        font-size: 3.5vw;
        word-break: break-all;
    }
    #raspberry{
        margin:10px;
        font-size: 3.5vw;
        word-break: break-all;
    }
    #cyclon{
        margin:10px;
        font-size: 3.5vw;
        word-break: break-all;
    }
    #generator{
        margin:10px;
        font-size: 3.5vw;
        word-break: break-all;
    }
    #hacker{
        margin:10px;
        font-size: 3.5vw;
        word-break: break-all;
    }
    #platform{
        margin:10px;
        font-size: 3.5vw;
        word-break: break-all;
    }

</style>