<template>
    <footer>
        <div class="footer-top">
            <div class="container-footer-top">
                <div class="footer-top-left">
                    <ul class="list-items">
                        <li class="head-list"><h4>dc comics</h4>
                            <ul>
                                <li>Characters</li>
                                <li>Comics</li>
                                <li>Movies</li>
                                <li>TV</li>
                                <li>Games</li>
                                <li>Videos</li>
                                <li>News</li>
                            </ul>
                        </li>
                        <li class="head-list"><h4>shop</h4>
                            <ul>
                                <li>Shop DC</li>
                                <li>Shop DC Collectibles</li>
                            </ul>
                        </li>
                        <li class="head-list"><h4>dc</h4>
                            <ul>
                                <li>Terms Of Use</li>
                                <li>Privacy policy (New)</li>
                                <li>Ad Choices</li>
                                <li>Advertising</li>
                                <li>Jobs</li>
                                <li>Subscription</li>
                                <li>Talent Workshops</li>
                                <li>CPSC Certificates</li>
                                <li>Ratings</li>
                                <li>Shop Help</li>
                                <li>Contact Us</li>
                            </ul>
                        </li>
                        <li class="head-list"><h4>sites</h4>
                            <ul>
                                <li>DC</li>
                                <li>MAD Magazine</li>
                                <li>DC Kids</li>
                                <li>DC Universe</li>
                                <li>DC Power Visa</li>
                            </ul>
                        </li> 
                    </ul>
                </div>
                <div class="footer-top-right"></div>
            </div>
        </div>
        <div class="footer-bottom"></div>
    </footer>
</template>

<script>
export default {

}
</script>

<style lang="scss" scoped>
    .footer-top {
        height: 400px;
        background-image: url('@/img/footer-bg.jpg');
        .container-footer-top {
            max-width: 1200px;
            margin: auto;
            display: flex;
            height: 100%;
            .list-items {
                list-style: none;
                height: 100%;
                width: 50%;
                margin-top: 3rem;
                display: flex;
                flex-direction: column;
                flex-wrap: wrap;
                color: #929292;   
                h4 {
                    text-transform: uppercase;
                    color: white;
                }
                ul {
                    list-style: none;
                    margin-left: -40px;
                }
            }
           
            .footer-top-left, .footer-top-right {
                width: 50%;
            }

            .footer-top-right {
                background-image: url('@/img/dc-logo-bg.png');
                background-size: cover;
                background-position: center;
            }
        }
    }

    .footer-bottom {
        height: 200px;
        background-color: #303030;
    }
</style>

<!-- <li class="head-list"><h4>dc comics</h4>
    <ul>
        <li>characters</li>
        <li>Comics</li>
        <li>Movies</li>
        <li>TV</li>
        <li>Games</li>
        <li>Videos</li>
        <li>News</li>
    </ul>
</li>
<li class="head-list"><h4>shop</h4>
    <ul>
        <li>Shop DC</li>
        <li>Shop DC Collectibles</li>
    </ul>
</li>
<li class="head-list"><h4>dc</h4>
    <ul>
        <li>Terms Of Use</li>
        <li>Privacy policy (New)</li>
        <li>Ad Choices</li>
        <li>Advertising</li>
        <li>Jobs</li>
        <li>Subscription</li>
        <li>Talent Workshops</li>
        <li>CPSC Certificates</li>
        <li>Ratings</li>
        <li>Shop Help</li>
        <li>Contact Us</li>
    </ul>
</li>
<li class="head-list"><h4>sites</h4>
    <ul>
        <li>DC</li>
        <li>MAD Magazine</li>
        <li>DC Kids</li>
        <li>DC Universe</li>
        <li>DC Power Visa</li>
    </ul>
</li> -->








<!-- <div class="footer-top">
    <div class="container-footer-top">
        <div class="footer-left">
            <ul class="list-footer">
                <li class="head-list">dc comics
                    <ul class="list-items">
                        <li>characters</li>
                        <li>Comics</li>
                        <li>Movies</li>
                        <li>TV</li>
                        <li>Games</li>
                        <li>Videos</li>
                        <li>News</li>
                    </ul>
                </li>
                <li class="head-list">shop
                    <ul class="list-items">
                        <li>Shop DC</li>
                        <li>Shop DC Collectibles</li>
                    </ul>
                </li>
                <li class="head-list">dc
                    <ul class="list-items">
                        <li>Terms Of Use</li>
                        <li>Privacy policy (New)</li>
                        <li>Ad Choices</li>
                        <li>Advertising</li>
                        <li>Jobs</li>
                        <li>Subscription</li>
                        <li>Talent Workshops</li>
                        <li>CPSC Certificates</li>
                        <li>Ratings</li>
                        <li>Shop Help</li>
                        <li>Contact Us</li>
                    </ul>
                </li>
                <li class="head-list">sites
                    <ul class="list-items">
                        <li>DC</li>
                        <li>MAD Magazine</li>
                        <li>DC Kids</li>
                        <li>DC Universe</li>
                        <li>DC Power Visa</li>
                    </ul>
                </li>
            </ul>
        </div>
        <div class="footer-right"><img src="@/img/dc-logo-bg.png" alt=""></div>
    </div>
</div>

 .footer-left {
                display: flex;
                flex-direction: column;
                flex-wrap: wrap;
                align-items: space-around;
                .list-footer {
                    display: flex;
                    .head-list {
                        text-transform: uppercase;
                        color: white;
                        list-style: none;
                        .list-items {
                            list-style: none;
                            color: #929292;
                        }
                    }
                }
            } -->