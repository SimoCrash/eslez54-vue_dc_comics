<template>
  <main>
    <div class="main-top">
        <div class="content">
            <h1>-- Content Goes Here --</h1>
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
export default {

}
</script>

<style lang="scss" scoped>
    $width-max: 1200px;
    .main-top {
        background-color: #1c1c1c;
        height: 200px;
        width: 100%;
        display: flex;
        align-items: center;
        .content {
            min-width: $width-max;
            margin: auto;
            h1 {
            color: white;
            }
        }
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