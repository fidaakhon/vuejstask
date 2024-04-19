<script setup>
import IconCommunity from './icons/IconCommunity.vue';
import CarretUp from './icons/CarretUp.vue';
</script>

<template>
    <div class="container">
        <div class="navbar">
            <div class="logos">
                <div class="logo1">
                    <img src="../assets/image.png" class="logo" alt="logo" />
                    <h1>Streamed</h1>
                </div>
                <div class="logo2">
                    <img src="../assets/home.png" class="homeLogo" alt="logo" />
                </div>
            </div>
            <div class="searchManu">khan</div>
        </div>

        <div class="counting">
            <div class="tasks">
                <p>Total project <span class="greenText">
                        <CarretUp /> 2
                    </span></p>
                <h1 class="boldNumber">7</h1>
            </div>
            <div class="tasks">
                <p>Total Tasks<span class="greenText">
                        <b-icon icon="bar-chart-fill"></b-icon>4
                    </span></p>
                <h1 class="boldNumber">49</h1>
            </div>
            <div class="tasks">
                <p>Assigned Tasks<span class="redText">
                        <ArrowDropDownIcon />3
                    </span></p>
                <h1 class="boldNumber">12</h1>
            </div>
            <div class="tasks">
                <p>Total project <span class="greenText">
                        <ArrowDropUpIcon />1
                    </span></p>
                <h1 class="boldNumber">6</h1>
            </div>
            <div class="tasks">
                <p>Total project <span class="greenText">
                        <ArrowDropUpIcon />2
                    </span></p>
                <h1 class="boldNumber">3</h1>
            </div>
        </div>
    </div>

</template>

<style scoped>
body {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

.container {
    width: 100vw;
}

.navbar {
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 10px 20px;
    background-color: #fff;
    border: 1px solid #f4f2f2;
    width: 100%;
    margin: 0;
}

.logos {
    display: flex;
    justify-content: space-between;
    width: 22vw;
}

.logo1 {
    display: flex;
}

.logo1 h1 {
    font-size: 1rem;
    font-weight: 700;
    margin-left: 10px;

}

.logo {
    width: 26.32px;
    height: 30.12px;
    gap: 0px;
    opacity: 0px;

}

.homeLogo {
    width: 8rem;
    height: 30.12px;
    gap: 0px;
    opacity: 0px;

}

.counting {
    display: flex;
    border: collapse;
    border: 1px solid rgb(234, 228, 228);
    border-radius: 10px;
    justify-content: space-between;
    margin-top: 2vh;
    margin-left: 3vw;
    margin-right: 3vw;
    /* padding: 1rem; */
}

.tasks {
    width: 17vw;
    height: 13vh;
    display: flex;
    flex-direction: column;
    justify-content: center;
    padding: 15px;
    border: collapse;
    border: 1px solid rgb(234, 228, 228);
    border-radius: 10px;
}

.greenText {
    color: #2CC171;
}

.redText {
    color: #FF0000;
}

.boldNumber {
    font-size: 2rem;
    font-weight: 700;
}

@media only screen and (max-width: 768px) {}
</style>