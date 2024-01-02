<template>
    <div id="expertise">
        <h1 id="title">Chain Chimp</h1>
        <h2>
            A Glimpse into Chain Chimp's Expertises and Achievements
        </h2>
        <div id="mobile-panels">
            <div id="mobile-panel-1" class="mobile-panel">
                <h1>
                    <span>NFTs</span>
                     — Branding, Design, Minting & Listing strategy on major market places
                </h1>
                <img src="@/../public/images/phone_frame_1.png" alt="">
            </div>

            <div id="mobile-panel-2" class="mobile-panel">
                <img src="@/../public/images/phone_frame_2.png" alt="">
                <h1>
                    <span>Partnership Reveal Quizz</span>
                     — Creation & Execution of Quizz type of engagement for your and partners project
                </h1>
            </div>

            <div id="mobile-panel-3" class="mobile-panel">
                <h1>
                    <span>Meme Campaign</span> — making your meme coin campaign just the way you imagined it
                </h1>
                <img src="@/../public/images/phone_frame_3.png" alt="">
            </div>

            <div id="mobile-panel-4" class="mobile-panel">
                <img src="@/../public/images/phone_frame_4.png" alt="">
                <h1>
                    <span>TestNet & Bug Bounty campaigns</span> or any other type of engagement suitable for your Platform and DApp
                </h1>
            </div>
        </div>
        <div id="laptop-panel">
            <LaptopPanel></LaptopPanel>
        </div>
    </div>
</template>

<style scoped>
@import '@/assets/fonts/fonts.css';

* {
    margin: 0px;
    -webkit-text-stroke: inherit;
    -webkit-text-stroke: initial;
    -webkit-text-stroke: revert;
    -webkit-text-stroke: revert-layer;
    -webkit-text-stroke: unset;
}

#expertise {
    width: 90%;
    max-width: 1520px;
    margin: 100px 80px;
    display: flex;
    gap: 90px;
    flex-direction: column;
    align-items: center;
    background-image: url('@/../public/images/big_hero_image.png');
    background-position: top center;
    background-size: 100%;
    background-repeat: no-repeat;
}


#title {
    color: #FF9C2D;
    font-family: Baloo;
    font-size: 112px;
    font-style: normal;
    font-weight: 400;
    line-height: normal;
    -webkit-text-stroke: 4.5px black;
}

h2 {
    color: #F0F3F6;
    text-align: center;
    font-family: 'Khula', sans-serif;
    font-size: 100px;
    font-style: normal;
    font-weight: 400;
    line-height: 110%; /* 110px */
    letter-spacing: -3px;
}

#mobile-panels {
    display: flex;
    gap: 38px;
    width: 100%;
    align-items: flex-end;
    overflow-x: scroll;
    height: 570px;
    justify-content: flex-start;
}

#mobile-panels::-webkit-scrollbar {
    display: none;
}

.mobile-panel {
    width: 100%;
    min-width: 210px;
    height: 520px;
    border-radius: 24px;
    background-repeat: no-repeat;
    display: flex;
    flex-direction: column;
    position: relative;
    overflow: hidden;
    justify-content: space-between;
}

#mobile-panel-1 {
    background-color: #F8F8FA;
}

#mobile-panel-2 {
    background-color: #C9DCF7;
}

#mobile-panel-3 {
    background-color: #D4DEE8;
}

#mobile-panel-4 {
    background-image: linear-gradient(180deg, rgba(0, 0, 0, 0) 0%, #C8CAFF 0%, #E4CFFF 100%); /* Set the background color to be transparent */
    border-radius: 24px;
    position: relative;
    z-index: 1;
    display: flex;
    flex-direction: column;
    justify-content: flex-end;
    overflow: visible;
}

.mobile-panel h1 {
    text-align: left;
    color: #666;
    font-family: Product Sans;
    font-size: 22px;
    font-style: normal;
    font-weight: 400;
    line-height: 115%;
    letter-spacing: -0.44px;
}

.mobile-panel h1 span {
    color: #212;
    font-weight: 700;
}

.mobile-panel img {
    align-self: flex-end;
}

#mobile-panel-1 h1 {
    margin: 30px 30px 0px 30px;
}

#mobile-panel-1 img {
    margin-top: -50px;
}

#mobile-panel-2 {
    justify-content: flex-end;
}

#mobile-panel-2 h1 {
    margin: 0px 30px 30px 30px;
}

#mobile-panel-2 img {
    position: absolute;
    top: -50px;
}

#mobile-panel-3 h1 {
    margin: 30px 30px 0px 30px;
}

#mobile-panel-4 img {
    position:absolute;
    top: -50px;
    left: 24px;
}

#mobile-panel-4 h1 {
    margin: 0px 30px 30px 30px;
}


#laptop-panel {
    width: 100%;
    display: flex;
    align-items: center;
    flex-direction: column;
}

@media screen and (max-width: 1600px) {
    #expertise {
        padding-top: 120px;
        gap: 60px;
    }

    #title {
        font-size: 100px;
    }

    h2 {
        font-size: 84px;
        margin: 0px 10px;
    }

    .mobile-panel {
        height: 440px;
    }

    .mobile-panel h1 {
        font-size: 21px;
    }

    #mobile-panel-2 img {
        top: -20px;
        width: 90%;
    }

    #mobile-panel-3 img {
        width: 90%;
    }

    #mobile-panel-4 img {
        width: 80%;
        position:absolute;
        top: -50px;
        left: 28px;
    }

}

@media screen and (max-width: 1440px) {
    #expertise {
        gap: 40px;
    }

    h2 {
        font-size: 75px;
    }

    #mobile-panels {
        gap: 30px;
        height: 450px;
    }

    .mobile-panel {
        height: 390px;
    }

    .mobile-panel h1 {
        font-size: 18px;
    }

    #mobile-panel-1 img {
        width: 80%;
    }

    #mobile-panel-4 img {
        width: 75%;
        position:absolute;
        top: -45px;
        left: 34px;
    }
}

@media screen and (max-width: 1200px) {
    #expertise {
        margin: 100px 30px;
        gap: 35px;
    }

    #title {
        font-size: 84px;
    }

    h2 {
        font-size: 64px;
    }

    #mobile-panels {
        gap: 29px;
        height: 410px;
    }

    .mobile-panel {
        height: 340px;
    }

    .mobile-panel h1 {
        font-size: 15px;
    }

    #mobile-panel-1 h1 { margin: 25px 25px 0px 25px; }

    #mobile-panel-2 h1 { margin: 0px 25px 25px 25px; }

    #mobile-panel-3 h1 { margin: 25px 25px 0px 25px; }

    #mobile-panel-4 h1 { margin: 0px 25px 25px 25px; }
}

@media screen and (max-width: 1000px) {
    h2 {
        font-size: 40px;
        width: 70%;
    }
}

@media screen and (max-width: 600px) {
    #expertise {
        gap: 25px;
    }
    
    #title {
        font-size: 64px;
    }

    h2 {
        font-size: 34px;
        width: 90%;
        margin: 0;
    }
}

</style>

<script>
import LaptopPanel from '@/components/LaptopPanel.vue'

export default {
  // eslint-disable-next-line vue/multi-word-component-names
  name: 'Expertise',
  components: {
    LaptopPanel
  }
}
</script>
