<template>
  <div id="wrapper">
    <img src="@/../public/images/phone_frame_4.png" alt="">
    <div id="mobile-panel">
      <h1>
        <span>TestNet & Bug Bounty campaigns</span> or any other type of engagement suitable for your Platform and DApp
      </h1>
    </div>
  </div>
</template>

<style scoped>
* {
  margin: 0px;
}

#wrapper {
  border-radius: 24px;
  position: relative;
  height: 552px;
  display: flex;
  flex-direction: column;
  justify-content: flex-end;
}

#wrapper img {
  position: absolute;
  top: -32px;
  left: 18px;
  z-index: 2;
  border-radius: 24px;
}

#mobile-panel {
  position: relative;
  z-index: 1;
   background-image: linear-gradient(180deg, rgba(0, 0, 0, 0) 0%, #C8CAFF 0%, #E4CFFF 100%); /* Set the background color to be transparent */
  max-width: 345px;
  height: 520px;
  border-radius: 24px;
  display: flex;
  flex-direction: column;
  justify-content: flex-end;
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
  name: 'MobilePanel4'
};
</script>
