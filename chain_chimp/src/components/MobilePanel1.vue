<template>
<div id="wrapper">
    <div id="mobile-panel">
        <h1>
            <span>NFTs</span> — Branding, Design, Minting & Listing strategy on major market places
        </h1>
    </div>
</div>
</template>

<style scoped>

* {
    margin: 0px;
}

#wrapper {
    height: 552px;
    display: flex;
    flex-direction: column;
    justify-content: end;
}

#mobile-panel {
    max-width: 345px;
    height: 520px;
    border-radius: 24px;
    background-image: url('@/../public/images/phone_frame_1.png');
    background-repeat: no-repeat;
    background-position: bottom right;
    background-color: #F8F8FA;
}

h1 {
    max-width: 345px;
    text-align: left;
    margin: 40px 40px 0px 40px;
    color: #666;
    font-family: Product Sans;
    font-size: 22px;
    font-style: normal;
    font-weight: 400;
    line-height: 115%;
    letter-spacing: -0.44px;
}

h1 span {
    color: #212;
    font-weight: 700;
}

</style>

<script>
export default {
    name: 'MobilePanel1'
}
</script>