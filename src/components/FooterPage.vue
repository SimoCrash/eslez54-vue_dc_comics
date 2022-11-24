<template>
    <footer>
        <div class="footer-top">
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
            }
            .footer-right {
                
            }
        }
    }

    .footer-bottom {
        height: 200px;
        background-color: #303030;
    }
</style>

<!-- <li class="head-list"><h2>dc comics</h2>
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
<li class="head-list"><h2>shop</h2>
    <ul>
        <li>Shop DC</li>
        <li>Shop DC Collectibles</li>
    </ul>
</li>
<li class="head-list"><h2>dc</h2>
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
<li class="head-list"><h2>sites</h2>
    <ul>
        <li>DC</li>
        <li>MAD Magazine</li>
        <li>DC Kids</li>
        <li>DC Universe</li>
        <li>DC Power Visa</li>
    </ul>
</li> -->