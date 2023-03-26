<script>

import locandina from './locandina.vue';
export default {
    nome: 'Main',
    components: {
        locandina
    },
    data() {
        return {
            locandine: [
                {
                    "thumb": "https://cdn.europosters.eu/image/1300/posters/dc-comics-rebirth-i80856.jpg",
                    "series": "SUPER HEROES",
                },
                {
                    "thumb": "https://wallpaperaccess.com/full/3605002.jpg",
                    "series": "SUPERMAN AND THE BUDDIES",
                },
                {
                    "thumb": "https://cosmicbook.news/wp-content/uploads/2020/09/batman-robert-pattinson-promo-images-dc-fandome.jpg",
                    "series": "BATMAN",
                },
                {
                    "thumb": "https://m.media-amazon.com/images/W/IMAGERENDERING_521856-T1/images/I/A1I7AJS0WdL._AC_UF1000,1000_QL80_.jpg",
                    "series": "AQUAMAN",
                },
                {
                    "thumb": "https://mlpnk72yciwc.i.optimole.com/cqhiHLc.IIZS~2ef73/w:auto/h:auto/q:75/https://bleedingcool.com/wp-content/uploads/2022/04/0222DC117.jpg",
                    "series": "SUICIDE SQUAD",
                },
                {
                    "thumb": "https://static01.nyt.com/images/2020/03/07/arts/05robin-tim-cover/05robin-tim-cover-mobileMasterAt3x.jpg",
                    "series": "ROBIN",
                },
                {
                    "thumb": "https://cf-images.us-east-1.prod.boltdns.net/v1/static/5359769168001/bc425ba4-a6e2-49e6-97ca-02fcbf3af727/bc964855-5ada-4888-9a91-017127da6737/1280x720/match/image.jpg",
                    "series": "SPIDER MAN",
                },
                {
                    "thumb": "https://images.saymedia-content.com/.image/ar_1:1%2Cc_fill%2Ccs_srgb%2Cfl_progressive%2Cq_auto:eco%2Cw_1200/MTc0MzY2OTMxOTU5MTYyMjE2/dc-strange-superheroes.jpg",
                    "series": "LANTERNA VERDE",
                },
                {
                    "thumb": "https://upload.wikimedia.org/wikipedia/en/e/ed/The_Flash_Family.jpg",
                    "series": "FLESH",
                },
                {
                    "thumb": "https://www.panini.it/media/catalog/product/cache/dcdcea88706ab1684584701c5b27598d/M/1/M1ANNI009ISBN_0.jpg",
                    "series": "HARLEY QUINN ",
                },
                {
                    "thumb": "https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQ28u0uja0hfGfyTKISIzq1r_f40TDz1UKvjA&usqp=CAU",
                    "series": "BATMAN AND THE VILLAIN",
                },
                {
                    "thumb": "https://i.blogs.es/335457/dc-universe-online/450_1000.webp",
                    "series": "WONDER WOMAN",
                }
            ]
        }
    }
}
</script>


<template>
    <div class="main_container">
        <!-- background-img -->
        <div class="background"></div>
        <!-- background-img -->
        <div class="background_nero">
            <div class="button-top">
                <button>
                    <h3>CURRENT SERIES</h3>
                </button>
            </div>
            <!-- v-for -->
            <div class="container_cards">
                <locandina v-for="(locandina, index) in locandine" :key="index" :img="locandina.thumb"
                    :title="locandina.series">
                </locandina>
            </div>
            <!-- v-for -->
            <div class="button-bottom">
                <button>
                    <h4>LOAD MORE</h4>
                </button>
            </div>
        </div>
    </div>
</template>
<style lang="scss" scoped>
* {
    padding: 0;
    margin: 0;
    box-sizing: border-box;
}

.main_container {

    .background {
        background-image: url(/jumbotron.jpg);
        background-size: cover;
        background-repeat: no-repeat;
        background-size: 100%;
        height: 400px;
        width: 100%;
    }

    .background_nero {
        background-color: #1c1c1c;
    }
    .container_cards {
        display: flex;
        flex-wrap: wrap;
        justify-content: space-around;
        max-width: 1300px;
        margin: auto;
        padding: 50px 0;
    }

    button {
        display: flex;
        margin: auto;
        padding: 10px 50px;
        background-color: #0282f9;
        border: none;
        color: white;
        font-size: 16px;
        transition: all 0.4s ease-out;
        cursor: pointer;
    }
    
    .button-top {
        position: absolute;
        left: 360px;
        top: 520px;
    }

    .button-bottom {
        padding: 20px;
    }

    button:hover {
        transform: scale(1.1);
    }

   

}</style>