<script>
    import MediacenterAndRadio from "./Components/MediacenterAndRadio.svelte";
    import Welcoming from "./Components/Welcoming.svelte";
    import BIS from "./Components/nocBIS.svelte";
    import IKNA from "./Components/nocInfokomAndNeuroArchitecht.svelte";
    import IOT from "./Components/nilIoT.svelte";
    import Outro from "./Components/Outro.svelte";
    import Tios from "./Components/nocTios.svelte";
</script>




<main>
    <header>
        <img src="images/bonchlogo.jpg" alt="Лого СПбГУТ">
        <button class="btn-home" title="Домой">
            <img class="img-button" src="images/homebutton.png" alt="Кнопка 'Домой'">
        </button>
    </header>

    <Welcoming/>

    <hr color="white">

    <MediacenterAndRadio/>

    <hr color="#EBEDF0" class="spacer">

    <BIS/>

    <hr color="#EBEDF0" class="spacer">

    <IKNA/>

    <hr color="#EBEDF0" class="spacer">

    <IOT/>

    <hr color="#EBEDF0" class="spacer">

    <Tios/>

    <hr color="#EBEDF0" class="spacerBig">

    <Outro/>

</main>

<style>
    img{
        max-width: 40%;
        padding: 3%;
    }

    header{
        box-shadow: 0px 5px 5px gray ;
        padding: 0px;
        display: -webkit-flex;
        display: -ms-flex;
        display: flex;
        align-items: center;
        justify-content: space-between;

    }

    .img-button{
        max-width: 100%;
        max-height: 100%;
    }
    .btn-home{
        background-color: #FFFFFF;
        margin: 7px;
        margin-right: 10px;
        display: none;
    }
    .spacer{
        padding: 10px;
    }
    .spacerBig{
        padding: 50px;
    }

</style>

