<template>
<div id="navigation">
    <nav>
        <h1 id="title" @click="open_mainpage()">Chain Chimp</h1>
        <h2 class="section-link">Expertise</h2>
        <h2 class="section-link">Services</h2>
        <h2 class="section-link">Roadmap</h2>
        <h2 class="section-link" @click="scrollToTeam">Team</h2>
        <h2 class="section-link">Partners</h2>
        <a href="#" id="x-logo" class="socials-logo">
            <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" viewBox="0 0 16 16" fill="none">
            <path d="M9.67265 6.80662L15.3499 0.207275H14.0046L9.07502 5.93739L5.1378 0.207275H0.59668L6.55053 8.87222L0.59668 15.7926H1.94208L7.14782 9.74145L11.3058 15.7926H15.8469L9.67232 6.80662H9.67265ZM7.82993 8.94856L7.22669 8.08573L2.42685 1.22007H4.49331L8.36683 6.76088L8.97008 7.62371L14.0052 14.8259H11.9387L7.82993 8.94889V8.94856Z" fill="#212122"/>
            </svg>
        </a>
        <a href="#" id="telegram-logo" class="socials-logo">
            <svg xmlns="http://www.w3.org/2000/svg" width="20" height="16" viewBox="0 0 20 16" fill="none">
            <path fill-rule="evenodd" clip-rule="evenodd" d="M7.98077 10.2573L16.1372 3.58945C16.488 3.27193 16.0495 3.19255 15.611 3.43069L5.61277 9.14601L1.31531 7.95532C0.350565 7.71718 0.350565 7.08214 1.49071 6.68525L18.4175 0.811165C19.2069 0.493647 19.9085 0.969924 19.6454 2.08124L16.7512 14.3851C16.5757 15.2582 15.9618 15.4964 15.1725 15.0995L10.7873 12.1624L8.6824 13.9882C8.41929 14.2263 8.06848 14.2263 8.06848 13.9882L7.98077 10.2573Z" fill="#212122"/>
            </svg>
        </a>
        <a href="#" id="linktree-logo" class="socials-logo">
            <svg xmlns="http://www.w3.org/2000/svg" width="18" height="16" viewBox="0 0 18 16" fill="none">
            <path d="M6.78921 0.594095C6.50256 0.0298329 5.75726 0.0298329 5.47061 0.594095L0.540174 10.3747C0.310852 10.8762 0.654836 11.4405 1.17081 11.4405H4.49599V15.1396C4.49599 15.5157 4.78264 15.8292 5.12662 15.8292H7.07587C7.41985 15.8292 7.7065 15.5157 7.7065 15.1396V11.4405H6.78921C6.3879 11.4405 6.10124 11.127 6.04391 10.7508C6.04391 10.6254 6.04391 10.5001 6.10124 10.3734L8.85311 4.91886L6.78921 0.594095Z" fill="#212122"/>
            <path d="M11.1466 0.594095C11.4333 0.0298329 12.1786 0.0298329 12.4652 0.594095L17.3957 10.3747C17.625 10.8762 17.281 11.4405 16.765 11.4405H13.4972V15.1396C13.4972 15.5157 13.2105 15.8292 12.866 15.8292H10.8026C10.4587 15.8292 10.172 15.5157 10.172 15.1396V11.4405H11.0893C11.4906 11.4405 11.7773 11.127 11.8346 10.7508C11.8346 10.6254 11.8346 10.5001 11.7773 10.3734L9.02539 4.92012L11.1466 0.594095Z" fill="#212122"/>
            </svg>
        </a>
        <a href="#" id="mail-logo" class="socials-logo">
            <svg xmlns="http://www.w3.org/2000/svg" width="22" height="16" viewBox="0 0 22 16" fill="none">
            <path d="M2.34549 2L9.13175 6.61227L9.13401 6.61396C9.88754 7.11128 10.2645 7.3601 10.6774 7.45622C11.0424 7.54117 11.426 7.54117 11.791 7.45622C12.2043 7.36001 12.5824 7.11047 13.3372 6.61227C13.3372 6.61227 17.69 3.60594 20.1233 2M1.23438 11.8002V4.2002C1.23438 3.08009 1.23438 2.51962 1.47658 2.0918C1.68963 1.71547 2.02934 1.40973 2.44748 1.21799C2.92284 1 3.54559 1 4.79015 1H17.679C18.9236 1 19.545 1 20.0204 1.21799C20.4385 1.40973 20.7794 1.71547 20.9924 2.0918C21.2344 2.5192 21.2344 3.07899 21.2344 4.19691V11.8036C21.2344 12.9215 21.2344 13.4805 20.9924 13.9079C20.7794 14.2842 20.4385 14.5905 20.0204 14.7822C19.5455 15 18.9244 15 17.6823 15H4.7865C3.54437 15 2.92238 15 2.44748 14.7822C2.02934 14.5905 1.68963 14.2842 1.47658 13.9079C1.23438 13.4801 1.23438 12.9203 1.23438 11.8002Z" stroke="#272A32" stroke-linecap="round" stroke-linejoin="round"/>
            </svg>
        </a>
        <div id="nav-buttons">
            <a href="#"><div class="nav-button" id="nav-button-1">Community</div></a>
            <a href="#"><div class="nav-button" id="nav-button-2">Market News</div></a>
            <a href="#" @click="enter_comicbook()"><div class="nav-button" id="nav-button-3">Comic book</div></a>
        </div>
        <div @click="toggle_menu()" id="hamburger">
            <svg xmlns="http://www.w3.org/2000/svg" width="37" height="4" viewBox="0 0 37 4" fill="none">
            <path d="M2 2L35 2" stroke="#212122" stroke-width="2.03077" stroke-linecap="round"/>
            </svg>
            <svg xmlns="http://www.w3.org/2000/svg" width="24" height="3" viewBox="0 0 24 3" fill="none">
            <path d="M2 1.15381L22 1.15381" stroke="#212122" stroke-width="2.03077" stroke-linecap="round"/>
            </svg>
            <div>
            <svg xmlns="http://www.w3.org/2000/svg" width="6" height="3" viewBox="0 0 6 3" fill="none">
            <path d="M2 1.30762L4 1.30762" stroke="#212122" stroke-width="2.03077" stroke-linecap="round"/>
            </svg>
            <svg xmlns="http://www.w3.org/2000/svg" width="12" height="3" viewBox="0 0 12 3" fill="none">
            <path d="M2 1.30762L10 1.30762" stroke="#212122" stroke-width="2.03077" stroke-linecap="round"/>
            </svg>
            </div>
        </div>
    </nav>
    <hr>
    <MobileMenu :class="{'openMenu': active, 'mobile-menu': true}" />
</div>
</template>

<script>
import MobileMenu from '@/components/MobileMenu.vue';

export default {
    // eslint-disable-next-line vue/multi-word-component-names
    name: 'Navigation',
    components: {
        MobileMenu
    },
    data() {
        return {
            active: false
        }
    },
    methods: {
        enter_comicbook() {
            this.$router.push('/comicbook');
        },
        open_mainpage() {
            this.$router.push('/');
        },
        toggle_menu() {
            this.active = !this.active;
        },
        scrollToTeam() {
            const chimpTeamComponent = this.$refs.chimpTeamComponent;
            if (chimpTeamComponent) {
                const teamElement = chimpTeamComponent.$el;
                if (teamElement) {
                    teamElement.scrollIntoView({ behavior: 'smooth' });
                }
            }
        },
    }
}
</script>

<style scoped>
@import '@/assets/fonts/fonts.css';

.mobile-menu {
    position: absolute;
    width: 100vw;
    top: -100vh;
    background-color: #F6F6F6;
    border-radius: 0px 0px 32px 32px;
    display: none;
    z-index: 2;
    transition: top 1s ease;
    padding: 0;
}

.openMenu {
    top: 0px;
    transition: top 1s ease;
}

#navigation {
    width: 100%;
    margin: auto;
    background-color: #F6F6F6;
    background-size: cover;
    background-position: center;
    justify-content: left;
}

nav {
    max-width: 1520px;
    display: flex;
    flex-direction: row;
    justify-content: space-between;
    margin: 0px auto;
    padding: 40px 50px 15px;
    align-items: center;
    position: relative;
    z-index: 4;
    background-color: #F6F6F6;
}

#hamburger {
    display: none;
}

#title {
    color: #FF9C2D;
    font-family: Baloo;
    font-size: 26px;
    font-style: normal;
    font-weight: 400;
    line-height: normal;
    -webkit-text-stroke: 1.5px black;
    cursor: pointer;
}

.section-link {
    color: #000000;
    text-align: center;
    font-family: Product Sans;
    font-size: 16px;
    font-style: normal;
    font-weight: 400;
    letter-spacing: -0.32px;
    cursor: pointer;
}

.section-link:hover {
    color: #FF9C2D;
    transition: 0.1s;
}

svg:hover {
    transition: 0.1s;
    transform: scale(1.15);
}

.socials-logo {
    height: 30px;
}

#nav-buttons {
    display: flex;
    gap: 20px;
}

#nav-buttons a {
    text-decoration: none;
}

.nav-button {
    padding: 10px 20px;
    border-radius: 25px;
    border: 1px solid #212122;
    color: #000;
    font-family: Product Sans;
    font-size: 16px;
    font-style: normal;
    font-weight: 400;
    letter-spacing: -0.32px;
}

.nav-button:hover {
    background-color: #212122;
    color: #fff;
    transition: 0.1s;
}

#nav-button-3 {
    border: none;
    background-color: #FCD493;
}

#nav-button-3:hover {
    background-color: #ffaa49;
    color: #fff;
    transition: 0.1s;
}

hr {
    max-width: 1920px;
    margin: auto;
    color: #353539;
    opacity: 0.1;
    position: relative;
    z-index: 3;
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
    #title { font-size: 24px; }

    #main-part { margin: 96px auto; }

    #text-and-buttons h3 { font-size: 17px; }

    #text-and-buttons h1 { font-size: 64px; }

    #text-and-buttons h1 span { font-size: 64px; }

    #text-and-buttons p { font-size: 23px; }

    .section-link { font-size: 15px; }

    .nav-button { font-size: 15px; }

    #hero-image img { height: 530px; }

    .glow { 
        width: 480px;
        height: 520px;
        left: -100px;
        filter: blur(150px);
    }
}

@media screen and (max-width: 1440px) {    
    #title { font-size: 23px; }

    #main-part { margin: 96px auto; }

    #text-and-buttons h3 { font-size: 15px; }

    #text-and-buttons h1 { font-size: 52px; }

    #text-and-buttons h1 span { font-size: 52px; }

    #text-and-buttons p { font-size: 19px; }

    #hero-image img { height: 480px; }

    .section-link { font-size: 14px; }

    .nav-button { font-size: 14px; }

    .hero-button { font-size: 20px; }
}

@media screen and (max-width: 1280px) {    
    #title { font-size: 21px; }

    #main-part { margin: 72px auto; }

    #text-and-buttons h3 { font-size: 13px; }

    #text-and-buttons h1 { font-size: 44px; }

    #text-and-buttons h1 span { font-size: 44px; }

    #text-and-buttons p { font-size: 18px; }

    #hero-image img { height: 380px; }

    .section-link { font-size: 12px; }

    .nav-button { font-size: 12px; }

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

@media screen and (max-width: 1024px) {
    .section-link { display: none; }
    .nav-button { display: none; }
    .socials-logo { display: none; }

    #hamburger {
        display: flex;
        flex-direction: column;
        align-items: end;
        gap: 10px;
        margin-bottom: 10px;
    }

    #hamburger div {
        display: flex;
    }
    
    .mobile-menu {
        display: flex;
    }
}

#mobile-hero-image {
    display: none;
}

#mobile-paragraph {
    display: none;
}

@media screen and (max-width: 960px) {
    #hero-image { display: none; }
    #paragraph { display: none; }
    #mobile-paragraph { display: block; }

    nav {
        padding: 30px 30px 15px;
    }

    #title {
        font-size: 26px;
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