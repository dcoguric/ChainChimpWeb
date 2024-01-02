<template>
<div id="wrapper">
    <div id="mobile-panel">
        <h1>
            <span>Meme Campaign</span> — making your meme coin campaign just the way you imagined it
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
    background-image: url('@/../public/images/phone_frame_3.png');
    background-repeat: no-repeat;
    background-position: bottom center;
    background-color: #D4DEE8;
    display: flex;
    flex-direction: column;
    justify-content: start;
}

h1 {
    margin: 40px 40px 30px 40px;
    text-align: left;
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
    name: 'MobilePanel3'
}
</script>