<template>
<div id="wrapper">
    <div id="mobile-panel">
        <h1>
            <span>Partnership Reveal Quizz</span> — Creation & Execution of Quizz type of engagement for your and partners project
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
    background-image: url('@/../public/images/phone_frame_2.png');
    background-repeat: no-repeat;
    background-position: top center;
    background-color: #C9DCF7;
    display: flex;
    flex-direction: column;
    justify-content: end;
}

h1 {
    margin: 0px 40px 30px 40px;
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
    name: 'MobilePanel2'
}
</script>