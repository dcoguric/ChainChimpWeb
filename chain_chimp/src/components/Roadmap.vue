<template>
    <div id="roadmap">
        <h1>ChainChimp DAO Roadmap</h1>
        <p>Jungle trail of strategic milestones propelling Chain Chimp to the forefront of crypto innovation</p>
        <div id="panel">
            <div id="leading-elements">
                    <div @mouseenter="marketing_highlight()" @mouseleave="marketing_highlight()" id="leading-element-1" class="leading-element">Marketing</div>
                    <div @mouseenter="community_highlight()" @mouseleave="community_highlight()" id="leading-element-2" class="leading-element">Community</div>
                    <div @mouseenter="business_highlight()" @mouseleave="business_highlight()" id="leading-element-3" class="leading-element">Business</div>
                    <div @mouseenter="technology_highlight()" @mouseleave="technology_highlight()" id="leading-element-4" class="leading-element">Technology</div>
            </div>
            <div id="majority">
                
            <div id="top-row">
                <div @mouseenter="q42023_highlight('q42023')" @mouseleave="q42023_highlight('q42023')">Q4 2023</div>
                <div @mouseenter="q42023_highlight('q12024')" @mouseleave="q42023_highlight('q12024')">Q1 2024</div>
                <div @mouseenter="q42023_highlight('q22024')" @mouseleave="q42023_highlight('q22024')">Q2 2024</div>
                <div @mouseenter="q42023_highlight('q32024')" @mouseleave="q42023_highlight('q32024')">Q3 2024</div>
                <div @mouseenter="q42023_highlight('q42024')" @mouseleave="q42023_highlight('q42024')">Q4 2024</div>
            </div>
                <div id="row-1" class="row">
                    <div class="subrow-1 subrow">
                        <div class="small-element marketing q42023 highlighted" id="element-1-1">Socials Setup</div>
                        <div class="small-element marketing q12024 q22024" id="element-1-2">Educational Content</div>
                        <div class="small-element marketing q22024 q32024" id="element-1-3">Podcast</div>
                    </div>
                    <div class="subrow-2 subrow">
                        <div class="small-element marketing community q42023 q12024" id="element-1-4">Comic Book</div>
                        <div class="small-element marketing community q22024 q32024" id="element-1-5">Air Drop Campaign</div>
                        <div class="small-element marketing community q32024 q42024" id="element-1-6">DAO Team Settup</div>
                    </div>
                </div>

                <div id="row-2" class="row">
                    <div class="subrow-1 subrow">
                        <div class="small-element community q12024" id="element-2-1">Community Campaigns</div>
                        <div class="small-element community q22024" id="element-2-2">DAO Model</div>
                        <div class="small-element community q32024" id="element-2-3">Air Drop Event</div>
                        <div class="small-element community q42024" id="element-2-4">Fully Fledged DAO</div>
                    </div>
                    <div class="subrow-2 subrow">
                        <div class="small-element community business q42023 q12024" id="element-2-5">Market News Feed</div>
                        <div class="small-element community business q22024 q32024" id="element-2-6">DAO  Contributors Applications</div>
                    </div>
                </div>
                
                <div id="row-3" class="row">
                    <div class="subrow-1 subrow">
                        <div class="small-element business q42023" id="element-3-1">Branding</div>
                        <div class="small-element business q12024 q22024" id="element-3-2">Services</div>
                        <div class="small-element business q42024" id="element-3-3">CEX Listing</div>
                    </div>
                    <div class="subrow-2 subrow">
                        <div class="small-element business technology q22024 q32024" id="element-3-4">Chimp DAO NFTs</div>
                        <div class="small-element business technology q32024 q42024" id="element-3-5">DEX Listing</div>
                    </div>
                </div>
                
                <div id="row-4" class="row">
                    <div class="subrow-1 subrow">
                        <div class="small-element technology q42023 q12024" id="element-4-1">Website Design</div>
                        <div class="small-element technology q22024" id="element-4-2">Discord DAO Settup</div>
                        <div class="small-element technology q32024" id="element-4-3">TGE</div>
                        <div class="small-element technology q42024" id="element-4-4">DAO Pool</div>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<style scoped>
* {
    margin: 0;
    padding: 0;
}

.marketing_highlighted {
    box-shadow: 0 0 10px 5px #686FCA;
}

.community_highlighted {
    box-shadow: 0 0 10px 5px #FEF7DD;
}

.business_highlighted {
    box-shadow: 0 0 10px 5px #6693C9;
}

.technology_highlighted {
    box-shadow: 0 0 10px 5px #A9D3F1;
}

#roadmap {
    width: 100%;
    padding: 0px 40px;;
    display: flex;
    flex-direction: column;
    align-items: center;
    max-width: 1600px;
    margin: auto;
    padding-bottom: 200px;
    position: relative;
    z-index: 1;
    background-color: rgba(30, 30, 30, 0.47);
}

h1 {
    color: #F0F3F6;
    text-align: center;
    font-family: Product Sans;
    font-size: 110px;
    font-style: normal;
    font-weight: 700;
    line-height: 105%;
}

p {
    margin: 50px 0px;
    color: #E5E8ED;
    text-align: center;
    font-family: 'Product Sans Light';
    font-size: 30px;
    font-style: normal;
    font-weight: 400;
    line-height: 130%; /* 39px */
    letter-spacing: -0.6px;
}

#panel {
    width: 100%;
    background-image: url('@/../public/images/jungle_background.png');
    background-repeat: no-repeat;
    background-size: cover;
    background-position: center;
    border-radius: 20px;
    display: flex;
    gap: 20px;
    height: fit-content;
    padding-bottom: 20px;
    overflow: hidden;
}

#leading-elements {
    display: flex;
    flex-direction: column;
    justify-content: flex-end;
    gap: 95px;
    width: 130px;
    margin-left: 20px;
    padding-bottom: 30px;
    cursor: default;
}

#leading-elements div {
    height: 75px;
    font-family: 'Product Sans';
}

#leading-element-1 {
    border-color: #686FCA;
    color: #686FCA;
}

#leading-element-2 {
    border-color: #FEF7DD;
    color: #FEF7DD;
}
#leading-element-3 {
    border-color: #6693C9;
    color: #6693C9;
}
#leading-element-4 {
    border-color: #A9D3F1;
    color: #A9D3F1;
}


#majority {
    display: flex;
    flex-direction: column;
    gap: 40px;
    width: 100%;
    overflow: scroll;
    padding-bottom: 30px;
}

#majority::-webkit-scrollbar {
            height: 15px;
            background: transparent; 
        }

#majority::-webkit-scrollbar-track {
            background-color: transparent; 
        }

#majority::-webkit-scrollbar-thumb {
            background-color: rgba(10, 10, 10, 0.45);
            border-radius: 15px;
        }

#majority::-webkit-scrollbar-thumb:hover {
            background-color: rgba(10, 10, 10, 0.75);
}

#majority::-webkit-scrollbar-corner {
            background-color: transparent;

}

#top-row {
    margin-top: 30px;
    display: flex;
    justify-content: space-around;
    gap: 14px;
    min-width: 1110px;
    cursor: default;
    padding-left: 15px;
}

#top-row div {
    width: 100%;
    display: flex;
    padding: 15px 12.433px;
    justify-content: center;
    align-items: center;
    color: #F0F3F6;
    font-family: Product Sans;
    font-size: 20px;
    font-style: normal;
    font-weight: 400;
    line-height: 120%; /* 24px */
    letter-spacing: -0.4px;
    border-radius: 25px;
    border: 2px solid #FE9D31;
}

#top-row div:hover {
    box-shadow: 0 0 10px 5px #FE9D31;
}

.row {
    display: flex;
    flex-direction: column;
    gap: 25px;
    min-width: 1110px;
}

.subrow {
    position: relative;
    display: flex;
    align-items: center;
}

.leading-element {
    width: 126px;
    height: 79px;
    display: flex;
    align-items: center;
    justify-content: center;
    border-radius: 25px;
    border: 2px solid;
    font-family: Product Sans;
    font-size: 20px;
    font-style: normal;
    font-weight: 400;
    line-height: 120%; /* 24px */
    letter-spacing: -0.4px;
}

#row-1 .leading-element {
    color: #686FCA;
    border-color: #686FCA;
}

#row-2 .leading-element {
    color: #FEF7DD;
    border-color: #FEF7DD;
}

#row-3 .leading-element {
    color: #6693C9;
    border-color: #6693C9;
}

#row-4 .leading-element {
    color: #A9D3F1;
    border-color: #A9D3F1;
}

.small-element {
    height: fit-content;
    color: #F0F3F6;
    font-family: 'Product Sans Light';
    font-size: 20px;
    font-style: normal;
    font-weight: 400;
    line-height: 120%; /* 24px */
    letter-spacing: -0.4px;
    border-radius: 25px;
    border: 2px solid;
    padding: 15px 40px;
    display: flex;
    justify-content: center;
    align-items: center;
}

#row-1 .subrow-1 .small-element {
    border-color: #686FCA;
}

#row-2 .subrow-1 .small-element {
    border-color: #FEF7DD;
}

#row-3 .subrow-1 .small-element {
    border-color: #6693C9;
}

#row-4 .subrow-1 .small-element {
    border-color: #A9D3F1;
}

.row .subrow-2 .small-element {
    position: relative;
    padding: 15px 20px;
    border: none;
}

#row-1 .subrow-2 .small-element::before {
    content: "";
    position: absolute;
    top: 0;
    left: 0;
    right: 0;
    bottom: 0;
    border-radius: 24px;
    border: 2px solid transparent;
    background: linear-gradient(180deg,#686FCA,#FEF7DD) border-box;
    -webkit-mask: linear-gradient(#fff 0 0) padding-box,  linear-gradient(#fff 0 0);
    -webkit-mask-composite: destination-out;
    mask-composite: exclude;
}


#row-2 .subrow-2 .small-element::before {
    content: "";
    position: absolute;
    top: 0;
    left: 0;
    right: 0;
    bottom: 0;
    border-radius: 25px; 
    border: 2px solid transparent;
    background: linear-gradient(180deg,#FEF7DD,#6693C9) border-box;
    -webkit-mask: linear-gradient(#fff 0 0) padding-box,  linear-gradient(#fff 0 0);
    -webkit-mask-composite: destination-out;
    mask-composite: exclude;
}

#row-3 .subrow-2 .small-element::before {
    content: "";
    position: absolute;
    top: 0;
    left: 0;
    right: 0;
    bottom: 0;
    border-radius: 25px; 
    border: 2px solid transparent;
    background: linear-gradient(180deg,#6693C9,#A9D3F1) border-box;
    -webkit-mask: linear-gradient(#fff 0 0) padding-box,  linear-gradient(#fff 0 0);
    -webkit-mask-composite: destination-out;
    mask-composite: exclude;
}

.dimmed {
    opacity: 75%;
}

#element-1-1 {margin-left: 2%;}
#element-1-2 {margin-left: 13%;}
#element-1-3 {margin-left: 9%; padding: 15px 45px;}
#element-1-4 {margin-left: 15%; padding: 15px 50px;}
#element-1-5 {margin-left: 27%;}
#element-1-6 {margin-left: 5%; bottom: 45px;}

#element-2-1 {margin-left: 14%;}
#element-2-2 {margin-left: 6%; padding: 15px 60px;}
#element-2-3 {margin-left: 5%;}
#element-2-4 {margin-left: 4%;}
#element-2-5 {margin-left: 9%;}
#element-2-6 {margin-left: 27%;}

#element-3-1 {margin-left: 10%;}
#element-3-2 {margin-left: 21%; padding: 15px 70px; }
#element-3-3 {margin-left: 25%;}
#element-3-4 {margin-left: 53%; padding: 15px 50px; }
#element-3-5 {margin-left: 5%; padding: 15px 35px;;}

#element-4-1 {margin-left: 12%;}
#element-4-2 {margin-left: 14%;}
#element-4-3 {margin-left: 5%; padding: 15px 45px;}
#element-4-4 {margin-left: 8%;}


@media screen and (max-width: 1600px) {
    h1 {
        font-size: 100px;
    }

    .small-element {
        padding: 13px 30px;
        font-size: 18px;
    }
}

@media screen and (max-width: 1440px) {
    #roadmap {
        padding-left: 20px;
        padding-right: 20px;
    }
    
    h1 {
        font-size: 90px;
    }

    p {
        font-size: 27px;
        margin: 35px 0px;
    }

    .small-element {
        font-size: 17px;
    }

}

@media screen and (max-width: 800px) {
    #roadmap {
        padding: 0px 0px 150px;
    }
    
    h1 {
        font-size: 72px;
    }

    p {
        font-size: 24px;
        margin: 35px 5%;
    }

    #panel {
        border-radius: 0px;
        gap: 0px;
    }

    #leading-elements {
        margin-left: 8px;
        margin-right: 0px;
        padding-right: 8px;
    }

    #leading-elements div {
        padding: 10px;
        height: 70px;
        font-size: 15px;
    }

    #top-row {
        margin-top: 20px;
    }
}

@media screen and (max-width: 600px) {
    
    h1 {
        font-size: 48px;
        padding: 0px 10px;
    }

    p {
        font-size: 20px;
        margin: 35px 5%;
    }
}

</style>

<script>
export default {
    // eslint-disable-next-line vue/multi-word-component-names
    name: 'Roadmap',
    methods: {
        marketing_highlight() {
            const leading_element = document.getElementById('leading-element-1');
            leading_element.classList.toggle('marketing_highlighted');
            const elements = document.getElementsByClassName('marketing');
            for (let i = 0; i < elements.length; i++) {
                elements[i].classList.toggle('marketing_highlighted');
            }

            const dimmed = document.getElementsByClassName('small-element');
            for (let i = 0; i < dimmed.length; i++) {
                if (!dimmed[i].classList.contains('marketing')) dimmed[i].classList.toggle('dimmed');
            }
        },
        community_highlight() {
            const leading_element = document.getElementById('leading-element-2');
            leading_element.classList.toggle('community_highlighted');
            const elements = document.getElementsByClassName('community');
            for (let i = 0; i < elements.length; i++) {
                elements[i].classList.toggle('community_highlighted');
            }

            const dimmed = document.getElementsByClassName('small-element');
            for (let i = 0; i < dimmed.length; i++) {
                if (!dimmed[i].classList.contains('community')) dimmed[i].classList.toggle('dimmed');
            }
        },
        business_highlight() {
            const leading_element = document.getElementById('leading-element-3');
            leading_element.classList.toggle('business_highlighted');
            const elements = document.getElementsByClassName('business');
            for (let i = 0; i < elements.length; i++) {
                elements[i].classList.toggle('business_highlighted');
            }

            const dimmed = document.getElementsByClassName('small-element');
            for (let i = 0; i < dimmed.length; i++) {
                if (!dimmed[i].classList.contains('bussiness')) dimmed[i].classList.toggle('dimmed');
            }
        },
        technology_highlight() {
            const leading_element = document.getElementById('leading-element-4');
            leading_element.classList.toggle('technology_highlighted');
            const elements = document.getElementsByClassName('technology');
            for (let i = 0; i < elements.length; i++) {
                elements[i].classList.toggle('technology_highlighted');
            }

            const dimmed = document.getElementsByClassName('small-element');
            for (let i = 0; i < dimmed.length; i++) {
                if (!dimmed[i].classList.contains('technology')) dimmed[i].classList.toggle('dimmed');
            }
        },
        q42023_highlight(quarter) {
            const elements = document.getElementsByClassName(quarter);
            for (let i = 0; i < elements.length; i++) {
                if (elements[i].classList.contains('marketing')) {
                    elements[i].classList.toggle('marketing_highlighted');
                } else if (elements[i].classList.contains('community')) {
                    elements[i].classList.toggle('community_highlighted');
                } else if (elements[i].classList.contains('business')) {
                    elements[i].classList.toggle('business_highlighted');
                } else if (elements[i].classList.contains('technology')) {
                    elements[i].classList.toggle('technology_highlighted');
                }
            }

            const dimmed = document.getElementsByClassName('small-element');
            for (let i = 0; i < dimmed.length; i++) {
                if (!dimmed[i].classList.contains(quarter)) dimmed[i].classList.toggle('dimmed');
            }
        }


    }
}
</script>