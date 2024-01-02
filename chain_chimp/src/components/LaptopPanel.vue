<template>
  <div id="laptop-panel">
    <h2>
      -At Chain Chimp, we deliver the best experience, providing professional expertise in the world of crypto marketing
    </h2>
    <div id="glow"></div>
    <img src="@/../public/images/pc_frame.png" id="laptop-image" alt="Overlay Image">
    <img src="@/../public/images/icon_python.png" id="icon-1" alt="">
    <img src="@/../public/images/icon_cmc.png" id="icon-2" alt="">
    <img src="@/../public/images/icon_w.png" id="icon-3" alt="">
    <img src="@/../public/images/icon_eht.png" id="icon-4" alt="">
    <img src="@/../public/images/icon_uni.png" id="icon-5" alt="">
    <img src="@/../public/images/icon_cointele.png" id="icon-6" alt="">
  </div>
</template>

<style scoped>
@import '@/assets/fonts/fonts.css';

* {
  margin: 0px;
}

#laptop-panel {
  border-radius: 24px;
  background-color: #2F2F2F;
  overflow: hidden;
  display: flex;
  flex-direction: column;
  justify-content: space-between;
  position: relative;
}

h2 {
  max-width: 658px;
  margin: 80px 0px 40px;
  color: #828282;
  font-family: Product Sans;
  font-size: 22px;
  font-style: normal;
  font-weight: 400;
  line-height: 130%;
  letter-spacing: -0.44px;
}

#glow {
  width: 1409px;
  height: 400px;
  border-radius: 1409px;
  background: linear-gradient(91deg, #78C7FF 8.75%, #7886FF 64.64%, #8378FF 115.59%);
  background-position: bottom center;
  filter: blur(200px);
  position: absolute;
  top: 0;
  left: 50%;
  transform: translateX(-50%) translateY(80%);
  z-index: 1; /* Set a z-index for the glow */
}

#laptop-image {
  width: 760px;
  height: auto;
  z-index: 2; /* Set a higher z-index for the image to appear on top */
}

#icon-1 {
    width: 81px;
    height: 81px;
    opacity: 90%;
    position: absolute;
    top: 12%;
    left: 3%;
    z-index: 3;
}

#icon-2 {
    width: 108px;
    height: 108px;
    opacity: 60%;
    position: absolute;
    top: 40%;
    left: 14%;
    z-index: 3;
}

#icon-3 {
    width: 102px;
    height: 102px;
    position: absolute;
    top: 85%;
    left: 7.5%;
    z-index: 3;
}

#icon-4 {
    width: 110px;
    height: 120px;
    opacity: 100%;
    position: absolute;
    top: 23%;
    right: 4%;
    z-index: 3;
}

#icon-5 {
    width: 70px;
    height: 70px;
    opacity: 55%;
    position: absolute;
    top: 45%;
    right: 16%;
    z-index: 3;
}

#icon-6 {
    width: 100px;
    height: 100px;
    opacity: 45%;
    position: absolute;
    top: 77%;
    right: 8%;
    z-index: 3;
}

@media screen and (max-width: 1600px) {
    h2 {
      margin-top: 60px;
    }

    #laptop-image {
      width: 600px;
    }
}

@media screen and (max-width: 1440px) {
    h2 {
      margin-top: 40px;
    }

    #laptop-image {
      width: 500px;
    }
}

@media screen and (max-width: 1260px) {
    #laptop-image {
      width: 450px;
    }

    #icon-1 {
      width: 70px;
      height: 70px;
    }

    #icon-2 {
      width: 90px;
      height: 90px;
    }

    #icon-3 {
      width: 80px;
      height: 80px;
    }

    #icon-4 {
      width: 90px;
      height: 100px;
    }

    #icon-5 {
      width: 60px;
      height: 60px;
    }

    #icon-6 {
      width: 80px;
      height: 80px;
    }

}

@media screen and (max-width: 1000px) {
   h2 {
    font-size: 18px;
    width: 80%;
   }

    #laptop-image {
      width: 400px;
    }

    #icon-1 {
      width: 60px;
      height: 60px;
      opacity: 100%;
      z-index: 3;
      top: 77%;
    }

    #icon-2 {
      width: 60px;
      height: 60px;
      opacity: 100%;
      z-index: 3;
      top: 40%;
      left: 8%;
    }

    #icon-3 {
      width: 60px;
      height: 60px;
      opacity: 70%;
      z-index: 0;
      top: 60%;
      left: 15%;
    }
    
    #icon-4 {
      width: 70px;
      height: 70px;
      opacity: 100%;
      z-index: 3;
      top: 38%;
    }

    #icon-5 {
      width: 50px;
      height: 50px;
      top: 62%;
    }

    #icon-6 {
      width: 70px;
      height: 70px;
      opacity: 100%;
      z-index: 3;
      top: 85%;
    }

}

@media screen and (max-width: 600px) {
  h2 {
    font-size: 16px;
    margin: 30px 0px;
    width: 90%;
  }

  #laptop-image {
    width: 300px;
  }

  #icon-1 {
    width: 45px;
    height: 45px;
  }

  #icon-2 {
    width: 45px;
    height: 45px;
  }

  #icon-3 {
    display: none;
  }

  #icon-4 {
    width: 50px;
    height: 50px;
  }

  #icon-5 {
    display: none;
  }

  #icon-6 {
    width: 50px;
    height: 50px;
  }

}

</style>

<script>
export default {
  name: 'LaptopPanel'
}
</script>
