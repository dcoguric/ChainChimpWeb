<template>
<div id="chimp-team">
    <div id="glow-1" class="glow"></div>
    <div id="glow-2" class="glow"></div>
    <h1>Chimp Team</h1>
    <p>Meet the team shaping the future of crypto at Chain Chimp—passionate, innovative, and committed to transforming the digital experience</p>
    <div id="chimps">
        <div class="chimp" id="chimp-1">
            <img src="@/../public/images/chimp_1.png" alt="">
            <svg xmlns="http://www.w3.org/2000/svg" width="41" height="41" viewBox="0 0 41 41" fill="none">
            <rect x="2" y="2" width="37" height="37" rx="8" fill="#1E1E1E"/>
            <rect x="2" y="2" width="37" height="37" rx="8" stroke="#FF9D2F" stroke-width="4"/>
            <rect x="2" y="2" width="37" height="37" rx="8" stroke="black" stroke-opacity="0.2" stroke-width="4"/>
            <path d="M22.2833 19.1624L31.2178 9H29.1006L21.3427 17.8238L15.1466 9H8L17.3698 22.3432L8 33H10.1173L18.3098 23.6817L24.8534 33H32L22.2827 19.1624H22.2833ZM19.3833 22.4608L18.4339 21.1321L10.8802 10.5596H14.1323L20.2282 19.0919L21.1776 20.4206L29.1016 31.5113H25.8495L19.3833 22.4613V22.4608Z" fill="white"/>
            </svg>
            <div class="text">
                <h2>Chimp #1</h2>
                <h3>Discord Wizzard</h3>
            </div>
        </div>
        <div class="chimp" id="chimp-2">
            <img src="@/../public/images/chimp_2.png" alt="">
            <svg xmlns="http://www.w3.org/2000/svg" width="41" height="41" viewBox="0 0 41 41" fill="none">
            <rect x="2" y="2" width="37" height="37" rx="8" fill="#1E1E1E"/>
            <rect x="2" y="2" width="37" height="37" rx="8" stroke="#FF9D2F" stroke-width="4"/>
            <rect x="2" y="2" width="37" height="37" rx="8" stroke="black" stroke-opacity="0.2" stroke-width="4"/>
            <path d="M22.2833 19.1624L31.2178 9H29.1006L21.3427 17.8238L15.1466 9H8L17.3698 22.3432L8 33H10.1173L18.3098 23.6817L24.8534 33H32L22.2827 19.1624H22.2833ZM19.3833 22.4608L18.4339 21.1321L10.8802 10.5596H14.1323L20.2282 19.0919L21.1776 20.4206L29.1016 31.5113H25.8495L19.3833 22.4613V22.4608Z" fill="white"/>
            </svg>
            <div class="text">
                <h2>Chimp #2</h2>
                <h3>Marketing Degen</h3>
            </div>
        </div>
        <div class="chimp" id="chimp-3">
            <img src="@/../public/images/chimp_3.png" alt="">
            <svg xmlns="http://www.w3.org/2000/svg" width="41" height="41" viewBox="0 0 41 41" fill="none">
            <rect x="2" y="2" width="37" height="37" rx="8" fill="#1E1E1E"/>
            <rect x="2" y="2" width="37" height="37" rx="8" stroke="#FF9D2F" stroke-width="4"/>
            <rect x="2" y="2" width="37" height="37" rx="8" stroke="black" stroke-opacity="0.2" stroke-width="4"/>
            <path d="M22.2833 19.1624L31.2178 9H29.1006L21.3427 17.8238L15.1466 9H8L17.3698 22.3432L8 33H10.1173L18.3098 23.6817L24.8534 33H32L22.2827 19.1624H22.2833ZM19.3833 22.4608L18.4339 21.1321L10.8802 10.5596H14.1323L20.2282 19.0919L21.1776 20.4206L29.1016 31.5113H25.8495L19.3833 22.4613V22.4608Z" fill="white"/>
            </svg>
            <div class="text">
                <h2>Chimp #3</h2>
                <h3>Tech Geek</h3>
            </div>
        </div>
    </div>
</div>
</template>

<style scoped>
* {
    margin: 0;
}

#chimp-team {
    width: 100%;
    background-color: #1E1E1E;
    padding: 100px 0;
    position: relative;
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
}

.glow {
    width: 1322.568px;
    height: 837.05px;
    border-radius: 1322.568px;
    opacity: 0.12;
    position: absolute;
    top: -400px;
}

#glow-1 {
    background: radial-gradient(50.04% 50.1% at 50.04% 49.9%, #78C7FF 0%, rgba(120, 199, 255, 0.00) 96.38%);
}

#glow-2 {
    background: radial-gradient(50.04% 50.1% at 50.04% 49.9%, #8378FF 0%, rgba(131, 120, 255, 0.00) 96.38%);
}

h1 {
    color: #F0F3F6;
    text-align: center;
    font-family: Product Sans;
    font-size: 100px;
    font-style: normal;
    font-weight: 700;
    line-height: 105%;
}

p {
    color: #E5E8ED;
    text-align: center;
    font-family: Product Sans Light;
    font-size: 30px;
    font-style: normal;
    font-weight: 400;
    line-height: 130%; /* 39px */
    letter-spacing: -0.6px;
    max-width: 1188px;
    margin: 42px 0px;
}

#chimps {
    display: flex;
    flex-direction: row;
    align-items: center;
    justify-content: center;
    flex-flow: wrap;
    gap: 100px;
    width: 100%;
    padding: 0px 30px;
    max-width: 1520px;
}

.chimp {
    display: flex;
    position: relative;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    width: fit-content;
}

.chimp svg {
    position: absolute;
    top: 20px;
    right: 25px;
    z-index: 1;
}

.text {
    padding: 20px;
    width: 100%;
    background: linear-gradient(180deg, #6592C8 0%, #FE8103 100%);  
}

h2 {
    height: 33px;
    color: #FFF;
    font-family: Roboto;
    font-size: 24px;
    font-style: normal;
    font-weight: 400;
    line-height: normal;
}

h3 {
    color: #FFF;
    font-family: Roboto;
    font-size: 14px;
    font-style: normal;
    font-weight: 400;
    line-height: normal;
}

@media screen and (max-width: 1260px) {
    h1 {
        font-size: 80px;
    }

    p {
        font-size: 24px;
        width: 80%;
    }
}

@media screen and (max-width: 600px) {
    h1 {
        font-size: 60px;
    }

    p {
        font-size: 18px;
        width: 90%;
    }

    #chimps {
        gap: 50px;
        margin-top: 20px;
    }

    .chimp {
        width: 90%;
    }

    img {
        width: 80%;
    }

    .text {
        padding: 15px;
    }

    h2 {
        font-size: 21px;
    }

    h3 {
        font-size: 13px;
    }

}

@media screen and (max-width: 400px) {
    h1 {
        font-size: 50px;
    }
}

</style>

<script>
export default {
    name: 'ChimpTeam',
}
</script>