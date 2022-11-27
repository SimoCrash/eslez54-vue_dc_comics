<template>
  <main>
    <div class="main-top">
        <div class="container-bg">
            <div class="c-series">
            <h1>current series</h1>
        </div>
        </div>
    </div>
    <div class="main-center">
        <div class="container-card-film">
            <cardFilm
            v-for="objCard in arrCards"
            :key="objCard.series"
            class="card-film"
            :img-film="objCard.thumb"
            :title-film="objCard.series"
            />
        </div>
    </div>
    <div class="main-bottom">
        <ul>
            <li>
                <img src="@/img/buy-comics-digital-comics.png" alt="">
                <span>digital comics</span>
            </li>
            <li>
                <img src="@/img/buy-comics-merchandise.png" alt="">
                <span>dc merchandise</span>
            </li>
            <li>
                <img src="@/img/buy-comics-shop-locator.png" alt="">
                <span>subscription</span>
            </li>
            <li>
                <img src="@/img/buy-comics-subscriptions.png" alt="">
                <span>comics shop locator</span>
            </li>
            <li>
                <img src="@/img/buy-dc-power-visa.svg" alt="">
                <span>dc power</span>
            </li>
        </ul>
    </div>
  </main>
</template>

<script>
import cardFilm from '@/components/cardFilm.vue';

export default {
    name: 'MainPage',
    components: {
        cardFilm,
    },
    data(){
        return {
            arrCards: [
                    {
                        "thumb": "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2018/09/AC1000_DLX_162-001_HD_5ba13723281ab0.37845353.jpg?itok=ZsI-C5eX",
                        "price": "$19.99",
                        "series": "Action Comics",
                        "type": "comic book"
                    },
                    {
                        "thumb": "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2020/09/AV1976_01_300-001_HD_5f738f6e39ddd7.18205602.jpg?itok=VgdYdJ01",
                        "price": "$3.99",
                        "series": "American Vampire 1976",
                        "type": "comic book"
                    },
                    {
                        "thumb": "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/gn-covers/2018/08/AQMv4_UW_153-001_HD_5b7efa1745a9b8.08589135.jpg?itok=HPTtnrsb",
                        "price": "$16.99",
                        "series": "Aquaman",
                        "type": "graphic novel"
                    },
                    {
                        "thumb": "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2018/06/batgirl_v5_1_5b23e1f1124941.50950783.jpg?itok=VnrJah76",
                        "price": "$2.99",
                        "series": "Batgirl",
                        "type": "comic book"
                    },
                    {
                        "thumb": "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2018/09/BM_56_300-001_HD_5ba137a85c3bf3.33122291.jpg?itok=3FHJQYJZ",
                        "price": "$3.99",
                        "series": "Batman",
                        "type": "comic book"
                    },
                    {
                        "thumb": "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2018/09/BM_56_300-001_HD_5ba137a85c3bf3.33122291.jpg?itok=3FHJQYJZ",
                        "price": "$2.99",
                        "series": "Batman Beyond",
                        "type": "comic book"
                    },
                    {
                        "thumb": "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2019/08/BMSM_5d4361b7116261.74371456.jpg?itok=kEDR2OL8",
                        "price": "$3.99",
                        "series": "Batman/Superman",
                        "type": "comic book"
                    },
                    {
                        "thumb": "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2020/09/BMSMANN_01_300-001_HD_5f5ff17fa1d665.74704970.jpg?itok=azz5sfGk",
                        "price": "$4.99",
                        "series": "Batman/Superman Annual",
                        "type": "comic book"
                    },
                    {
                        "thumb": "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2020/09/BMTJWZ_01_300-001_HD_5f5ff2307dcb37.34652945.jpg?itok=VswVjLR8",
                        "price": "$5.99",
                        "series": "Batman: The Joker War Zone",
                        "type": "comic book"
                    },
                    {
                        "thumb": "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2020/08/cover-v2_5f40314645a734.37285065.png?itok=ImNM2QBY",
                        "price": "$6.99",
                        "series": "Batman: Three Jokers",
                        "type": "comic book"
                    },
                    {
                        "thumb": "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2020/10/BMWK_HQ_01_300-001_HD_5f7cb4945e13f6.89501032.jpg?itok=sVwALbUX",
                        "price": "$4.99",
                        "series": "Batman: White Knight Presents: Harley Quinn",
                        "type": "comic book"
                    },
                    {
                        "thumb": "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/gn-covers/2019/04/CTWv1_CC_144-001_HD_5ca5299a751963.53054221.jpg?itok=ooPaoLDq",
                        "price": "$16.99",
                        "series": "Catwoman",
                        "type": "graphic novel"
                    }
            ]
        }
        
    }

}
</script>

<style lang="scss" scoped>
    $width-max: 1200px;
    .main-top {
        background-image: url('https://d2lv662meabn0u.cloudfront.net/boing/dynamic/show/00000000/54/298621e1e503379dbd3e1745c698f75301418e81_1587054231.jpg');
        background-repeat: no-repeat;
        background-size: cover;
        height: 400px;
        width: 100%;
        .container-bg {
            max-width: $width-max;
            height: 100%;
            margin: auto;
            position: relative;
            .c-series {
                position: absolute;
                bottom: -10%;
                background-color: #0282F9;
                h1 {
                    color: white;
                    padding: .5rem;
                    text-transform: uppercase;
                }
            }
       
        }
    }

    .main-center {
        background-color: #1C1C1C;
        .container-card-film {
            padding: 4rem;
            max-width: $width-max;
            margin: auto;
            display: flex;
            flex-direction: row;
            flex-wrap: wrap;
            justify-content: flex-start;
            gap: 1rem;
        }
    }
    .card-film {
        width: calc((100% / 6) - 1rem);
        }
    .main-bottom {
        background-color: #0282F9;
        ul {
            height: 200px;
            max-width: $width-max;
            margin: auto;
            margin-top: 0;
            list-style: none;
            display: flex;
            align-items: stretch;
            gap: 1rem;
            color: white;
            li {
                display: flex;
                align-items: center;
                text-transform: uppercase;
                img {
                    height: 60px;
                    padding: 1rem;
                }
            }
        }

        
    }
</style>





















.container-list-item {
    display: flex;
    align-items: stretch;
    .list-item {
        display: flex;
        gap: 1rem;
        list-style: none;
        font-weight: bold;
        color: #4E5A66;
        align-items: center;
    }   