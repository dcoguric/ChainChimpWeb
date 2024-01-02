<template>
    <div id="hero-area" class="row">    
        <div id="main-part">
            <div id="text-and-buttons">
                <h3>
                    Inspired by innovation, driven by results, and fueled by passion, we're the force behind your blockchain success.
                </h3>
                <h1>Unlocking Crypto Success with Chain Chimp: 
                    <span>
                        Your Premier Marketing and Consulting Partner
                    </span>
                </h1>
                <p id="paragraph">
                    Your Complete Crypto Marketing Solution: Elevating your crypto project with expert social media management, strategic roadmap planning, seamless marketing execution, insightful consulting, and unparalleled connection and introductions to ecosystems, VCs, projects, influencers, developers and more ...
                </p>

                <div id="mobile-hero-image">
                    <img src="@/../public/images/hero_image.png" alt="">
                    <div class="glow"></div>
                </div>
                
                <p id="mobile-paragraph">
                    Your Complete Crypto Marketing Solution: Elevating your crypto project with expert social media management, strategic roadmap planning, seamless marketing execution, insightful consulting, and unparalleled connection and introductions to ecosystems, VCs, projects, influencers, developers and more ...
                </p>

                <div id="hero-buttons">
                    <div class="hero-button" id="hero-button-1">Contact Chimp Team</div>
                    <div class="hero-button" id="hero-button-2">One Pager</div>
                </div>
            </div>

            <div id="hero-image">
                <img src="@/../public/images/hero_image.png" alt="">
                <div class="glow"></div>
            </div>
        </div>
    </div>
</template>

<style scoped>
@import '@/assets/fonts/fonts.css';

#hero-area {
    margin: auto;
    background-color: #F6F6F6;
    border-radius: 0px 0px 32px 32px;
    background-size: cover;
    background-position: center;
    justify-content: left;
    padding: 0px 50px;
    width: 100%;
}

#main-part {
    margin: 120px auto;
    width: fit-content;
    max-width: 1920px;
    display: flex;
    flex-direction: row;
}

#text-and-buttons {
    display: flex;
    flex-direction: column;
    padding-right: 40px;
}

#text-and-buttons h3 {
    color: #000;
    text-shadow: 0px 4px 4px rgba(0, 0, 0, 0.25);
    font-family: Product Sans;
    font-size: 18px;
    font-style: normal;
    font-weight: 400;
    line-height: 120%; /* 21.6px */
    letter-spacing: -0.36px;
    text-align: left;
}

#text-and-buttons h1 {
    max-width: 1100px;
    color: #212122;
    font-family: Product Sans;
    font-size: 80px;
    font-style: normal;
    font-weight: 400;
    line-height: 104%; /* 83.2px */
    letter-spacing: -2.4px;
    text-align: left;
    margin: 16px 0 42px;
}

#text-and-buttons h1 span {
    color: transparent;
    background: linear-gradient(180deg, #FF9C2D 50%, #212122);
    -webkit-background-clip: text;
    background-clip: text;
    font-family: Product Sans;
    font-size: 84px;
    font-style: normal;
    font-weight: 400;
    line-height: 104%;
    letter-spacing: -2.4px;
}

#text-and-buttons p {
    max-width: 816px;
    text-align: left;
    color: #000;
    text-shadow: 0px 4px 4px rgba(0, 0, 0, 0.25);
    font-family: Product Sans;
    font-size: 27px;
    font-style: normal;
    font-weight: 400;
    line-height: 120%; /* 32.4px */
    letter-spacing: -0.54px;
}

#hero-buttons {
    width: fit-content;
    display: flex;
    gap: 40px;
    margin-top: 50px;
}

.hero-button {
    display: flex;
    padding: 14px 30px;
    justify-content: center;
    align-items: center;
    border-radius: 70px;
    border: 2px solid #2B2B2B;
    font-family: Product Sans;
    font-size: 23px;
    font-style: normal;
    line-height: 120%; /* 27.6px */
    font-weight: 400;
    letter-spacing: -0.46px;

}

#hero-button-1 {
    color: #F6F6F6;
    background-color:  #2B2B2B;
    cursor: pointer;
}

#hero-button-1:hover {
    background-color: #101010;
    transition: 0.1s;
}

#hero-button-2 {
    color: #000;
    background-color: transparent;
    cursor: pointer;
}

#hero-button-2:hover {
    background-color: #ffaa49;
    border-color: #ffaa49;
    transition: 0.1s;
}

#hero-image {
    position: relative;
}

#hero-image img {
    position: relative;
    z-index: 1;
}

.glow {
    z-index: 0;
    position: absolute;
    bottom: -120px;
    right: 80px;
    width: 540px;
    height: 588px;
    transform: rotate(90deg);
    flex-shrink: 0;
    border-radius: 588px;
    opacity: 0.6;
    background: #FF9E2E;
    filter: blur(120px);
}

@media screen and (max-width: 1600px) {
    #main-part { margin: 96px auto; }

    #text-and-buttons h3 { font-size: 17px; }

    #text-and-buttons h1 { font-size: 64px; }

    #text-and-buttons h1 span { font-size: 64px; }

    #text-and-buttons p { font-size: 23px; }

    #hero-image img { height: 530px; }

    .glow { 
        width: 480px;
        height: 520px;
        left: -100px;
        filter: blur(150px);
    }
}

@media screen and (max-width: 1440px) {    
    #main-part { margin: 96px auto; }

    #text-and-buttons h3 { font-size: 15px; }

    #text-and-buttons h1 { font-size: 52px; }

    #text-and-buttons h1 span { font-size: 52px; }

    #text-and-buttons p { font-size: 19px; }

    #hero-image img { height: 480px; }

    .hero-button { font-size: 20px; }
}

@media screen and (max-width: 1280px) {
    #main-part { margin: 72px auto; }

    #text-and-buttons h3 { font-size: 13px; }

    #text-and-buttons h1 { font-size: 44px; }

    #text-and-buttons h1 span { font-size: 44px; }

    #text-and-buttons p { font-size: 18px; }

    #hero-image img { height: 380px; }

    .hero-button { font-size: 18px; }    

    #hero-buttons { margin-top: 30px; }

    .glow { 
        width: 400px;
        height: 430px;
        left: -100px;
        top: 100px;
        filter: blur(150px);
    }
}

#mobile-paragraph {
    display: none;
}

#mobile-hero-image {
    display: none;
}

@media screen and (max-width: 960px) {
    #hero-image { display: none; }
    #paragraph { display: none; }
    #mobile-paragraph { display: block; }

    #hero-area {
        padding: 0px 30px;
    }

    #main-part {
        flex-direction: column;
        margin: 60px auto;
    }

    #text-and-buttons {
        padding-right: 0px;
        margin: 0px auto;
    }

    #text-and-buttons p {
        text-align: center;
        font-size: 21px;
        margin: 15px;
        margin-top: 35px;
    }

    #text-and-buttons h3 {
        display: none;
    }

    #text-and-buttons h1 {
        font-size: 40px;
        text-align: center;
        margin-bottom: 20px;
    }

    #mobile-hero-image { 
        margin: 30px auto;
        display: block;
        position: relative;
    }

    #mobile-hero-image img {
        width: 80%;
        max-width: 450px;
        height: auto;
        position: relative;
        z-index: 1;;
    }

    .glow {
        width: 450px;
        height: 450px;
        position: absolute;
        z-index: 0;
        left: 5%;
        filter: blur(100px);
    }

    #hero-buttons {
        display: relative;
        z-index: 2;
        margin: 40px auto;
        justify-content: center;
        font-size: 21px;
    }
}

@media screen and (max-width: 600px) {
    #hero-area {
        padding: 0px 15px;
    }

    #main-part {
        margin: 30px auto;
    }

    #hero-buttons {
        flex-direction: column;
        gap: 20px;
        width: 100%;
    }

    .glow {
        width: 350px;
        height: 350px;
    }

    #mobile-paragraph {
        font-size: 16px;
    }
}

</style>

<script>
export default {
  name: 'HeroArea'
}
</script>