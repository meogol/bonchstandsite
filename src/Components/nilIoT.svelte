<script>
    let k = 0;
    function viewInfo(){
        k= k+1;
        if(k==1){
            document.getElementById("iotInfo").style.display="block";
        }
        else{
            k=0;
            document.getElementById("iotInfo").style.display="none";
        }
    }
</script>
<div class="IoT">
    <div id="textContainerIoT">
        <h1 id="IoT">НИЛ <br> "Лаборатория интернета вещей"</h1>
        <p id="IoTTextUnderHeader">Изучение<br>систем<br>Интернета вещей </p>
        <button class="PressMe" on:click={viewInfo}>Подробнее</button>
    </div>
    <img class="photo-IoT" src="images/IOT.jpg" alt="Лаборатория интернета вещей">
</div>
<div class="iotInfoHolder">
    <p id="iotInfo">
        Лаборатория Интернета Вещей<br><br>
        Лаборатория Интернета Вещей была создана в 2012 году на базе кафедры Сетей
        связи и передачи данных СПбГУТ. На сегодняшний день является единственной
        в России лабораторией, занимающейся комплексным исследованием Интернета
        Вещей. Лаборатория ориентирована на изучение систем IoT. У студентов есть
        возможность учиться создавать системы промышленного интернета вещей,
        вести мониторинг датчиков, а также объединять устройства в сеть с помощью
        современных и актуальных стандартов радиопередачи данных.<br>
        Чем занимается<br>
        • Научно-исследовательские работы<br>
        Анализ материалов и проведение поисковых теоретических и прикладных
        исследований<br>
        • Организация мероприятий<br>
        Проведение семинаров, лекций, конференций<br>
        • Прототипирование<br>
        Разработка концепции и подбор деталей для аппаратной части устройства,
        разработка макета и сопутствующего ПО, тестирование прототипа
        Возможности лаборатории<br>
        1. Разработка<br>
        Разработка IoT устройств и приложений Интернета вещей. Разработка и
        исследование летающих сенсорных сетей на базе квадрокоптеров общего
        пользования.<br>
        2. Тестирование<br>
        Тестирование взаимодействия Интернет вещей с сетями связи общего
        пользования. Тестирование совместимости Интернет Вещей.<br>
        3. Исследование<br>
        Исследование трафика M2M, VANET, IoT на базе модельных сетей
        лаборатории.<br>
        Исследования уязвимости Интернета Вещей.<br>
        4. Разработка стандартов и рекомендаций<br>
        Разработка проектов стандартов и рекомендаций для Исследовательской
        комиссии 20 «Интернет вещей, его приложения, включая Умные города и
        сообщества» Сектора стандартизации электросвязи Международного союза
        электросвязи.<br>
        5. Планирование<br>
        Планирование топологий гетерогенных сетей с учетом специфики сетей 5G.<br>
        6. Разработка методов идентификации<br>
        Разработка методов идентификации устройств Интернета вещей для борьбы с
        контрафактной ИКТ-продукцией при взаимодействии с подкомитетом ТК22/141 «Информационные технологии для Интернета Вещей».<br>
        Группа Вконтакте:<a href="https://vk.com/iotlab">https://vk.com/iotlab</a>
    </p>
</div>
<style>
    .IoT{
        background-color: white;
        display: -webkit-flex;
        display: -ms-flex;
        display: flex;
        align-items: center;
        max-width: 80%;
        margin-left: 10%;
    }
    .photo-IoT{
        margin-left: auto;
        margin-right: 5px;
        margin-bottom: 5px;
        margin-top: 5px;
        border-radius: 10px;
        height: auto;
        width: 100%;
        max-width: 180px;
    }
    #IoT{
        font-size: 3vw;
        font-family: Gilroy;
        margin-bottom: auto;
        margin-left: 5px;
    }
    #IoTTextUnderHeader{
        font-size: 2.5vw;
        display: block;
        margin-left: 5px;
    }
    #textContainerIoT{
        display: block;
        margin-left: 10px;
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
    iotInfoHolder{
        display: flex;
        max-width: 100%;
    }
    #iotInfo{
        display: none;
        margin:10px;
        font-size: 3.5vw;
        word-break: break-all;
    }
</style>