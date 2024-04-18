<script setup>
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

@media only screen and (max-width: 768px) {}
</style>