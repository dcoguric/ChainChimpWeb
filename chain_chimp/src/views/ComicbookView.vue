<template>
  <div id="comicbook">
    <Navigation />
    <div class="grid">
      <div v-for="(image, index) in images" :key="index" class="grid-item" @click="openModal(index)">
        <div class="preview" :style="{ backgroundImage: 'url(/images/comicbook_images/' + image + ')' }"></div>
      </div>
    </div>
    <div v-if="isModalOpen" class="modal active">
      <span class="close" @click="closeModal">&times;</span>
      <img :src="'/images/comicbook_images/' + images[currentIndex]" alt="Modal Image" />
      <button @click="prevImage" v-show="currentIndex > 0">Previous</button>
      <button @click="nextImage" v-show="currentIndex < images.length - 1">Next</button>
    </div>

    <div id="mobile-gallery">
        <div v-for="(image, index) in images" :key="index">
            <img :src="'/images/comicbook_images/' + image" alt="">
        </div>
    </div>
  </div>
</template>

<style scoped>
#comicbook {
  margin: 0 auto;
  background-color: #F6F6F6;
}

.grid {
  margin: 50px;
  display: grid;
  grid-template-columns: repeat(auto-fill, minmax(300px, 1fr));
  gap: 5px;
}

.grid-item {
  position: relative;
  min-height: 300px; /* Set a minimum height for the grid items */
}

.preview {
  width: 100%;
  height: 100%;
  background-size: cover;
  background-position: center;
  cursor: pointer;
}

.modal {
  display: none;
  position: fixed;
  z-index: 1;
  padding-top: 60px;
  left: 0;
  top: 0;
  width: 100%;
  height: 100%;
  overflow: auto;
  background-color: rgb(0, 0, 0);
  background-color: rgba(0, 0, 0, 0.9);
}

.modal.active {
  display: block;
}

.modal img {
  max-width: 60%;
  max-height: 80vh;
  margin: auto;
  display: block;
}

.close {
  position: absolute;
  top: 15px;
  right: 35px;
  font-size: 40px;
  color: #f1f1f1;
  cursor: pointer;
}

button {
  background-color: #fbbc3e;
  color: #212121;
  border: none;
  padding: 10px 15px;
  text-align: center;
  text-decoration: none;
  display: inline-block;
  font-size: 16px;
  margin: 15px;
  cursor: pointer;
  border-radius: 4px;
}

#mobile-gallery {
    display: none;
}

@media screen and (max-width: 700px) {
    .grid {
        display: none;
    }

    #mobile-gallery {
        display: flex;
        flex-direction: column;
        gap: 20px;
        margin-top: 35px;
    }

    #mobile-gallery img {
        width: 90%;
    }
}

</style>

<script>
import Navigation from "@/components/Navigation.vue";

export default {
  name: "ComicbookView",
  components: {
    Navigation,
  },
  data() {
    return {
      images: [
        "page1.jpg",
        "page2.jpg",
      ],
      isModalOpen: false,
      currentIndex: 0,
    };
  },
  methods: {
    openModal(index) {
      this.currentIndex = index;
      this.isModalOpen = true;
    },
    closeModal() {
      this.isModalOpen = false;
    },
    prevImage() {
      if (this.currentIndex > 0) {
        this.currentIndex--;
      }
    },
    nextImage() {
      if (this.currentIndex < this.images.length - 1) {
        this.currentIndex++;
      }
    },
  },
};
</script>