<template>
    <div id="partners">
        <h1>Our Partners & Frens</h1>
        <div id="partner-icons">
            <img src="@/../public/images/partner_1.png" alt="">
            <img src="@/../public/images/partner_2.png" alt="">
            <img src="@/../public/images/partner_3.png" alt="">
            <img src="@/../public/images/partner_4.png" alt="">
            <img src="@/../public/images/partner_5.png" alt="">
        </div>
        <h2>Powered by collaboration, Chain Chimp is proud to align with the Best</h2>
        <div id="glow-1" class="glow"></div>
        <div id="glow-2" class="glow"></div>
    </div>
</template>

<style scoped>
* {
    margin: 0;
}

#partners {
    width: 100%;
    margin: 100px auto 30px;
    padding-bottom: 100px;
    position: relative;
    overflow: hidden;
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

h2 {
    color: var(--Light-grayish-blue, #E5E8ED);
    text-align: center;
    font-family: Product Sans Light;
    font-size: 30px;
    font-style: normal;
    font-weight: 400;
    line-height: 130%;
    width: 80%;
    margin: auto;
}

#partner-icons {
    display: flex;
    justify-content: center;
    align-items: center;
    margin: 100px 30px;
    gap: 50px;
    position: relative;
    z-index: 2;
    flex-flow: wrap;
}

.glow {
    width: 1322.568px;
    height: 837.05px;
    border-radius: 1322.568px;
    opacity: 0.12;
    position: absolute;
    bottom: -400px;
    z-index: 1;
}

#glow-1 {
    background: radial-gradient(50.04% 50.1% at 50.04% 49.9%, #78C7FF 0%, rgba(120, 199, 255, 0.00) 96.38%);
    left: 2%;
}

#glow-2 {
    background: radial-gradient(50.04% 50.1% at 50.04% 49.9%, #8378FF 0%, rgba(131, 120, 255, 0.00) 96.38%);
    right: 2%;
}

@media screen and (max-width: 1200px) {
    h1 {
        font-size: 80px;
        margin: 0 5%;
    }
}

@media screen and (max-width: 600px) {
    h1 {
        font-size: 60px;
    }

    h2 {
        font-size: 24px;
    }

    #partner-icons {
        margin-top: 50px;
    }

    img {
        width: 65%;
    }
}

@media screen and (max-width: 400px) {
    h1 {
        font-size: 50px;
    }

    h2 {
        font-size: 20px;
    }
}

</style>

<script>
export default {
    // eslint-disable-next-line vue/multi-word-component-names
    name: 'Partners',
}
</script>