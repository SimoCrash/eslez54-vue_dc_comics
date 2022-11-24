<template>
    <header>
        <nav>
            <ul class="container-list">
                <li class="container-logo"><img src="@/img/dc-logo.png" alt=""></li>
                <li class="container-list-item">
                    <ul class="list-item">
                        <li>characters</li>
                        <li>comics</li>
                        <li>movies</li>
                        <li>tv</li>
                        <li>games</li>
                        <li>collectibles</li>
                        <li>videos</li>
                        <li>fans</li>
                        <li>news</li>
                        <li>shop</li>
                    </ul>
                </li>
            </ul>
        </nav>
    </header>
</template>

<script>
export default {

}
</script>

<style lang="scss" scoped>
    * {
        margin: 0;
        padding: 0;
        box-sizing: border-box;
    }

    nav {
        height: 150px;
        max-width: 1200px;
        margin: auto;
        display: flex;
        .container-list {
            display: flex;
            list-style: none;
            width: 100%;
            .container-logo {
                width: 40%;
                display: flex;
                justify-content: flex-start;
                align-items: center;
            }   
            .container-list-item {
                display: flex;
                align-items: stretch;
                .list-item {
                    display: flex;
                    gap: 1rem;
                    text-transform: uppercase;
                    list-style: none;
                    font-weight: bold;
                    color: #4E5A66;
                    align-items: center;
                }    
            }
        }
    }
</style>