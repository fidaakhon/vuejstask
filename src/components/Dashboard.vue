<script setup>
import IconCommunity from './icons/IconCommunity.vue';
import CarretUp from './icons/CarretUp.vue';
import Search from './icons/Search.vue';
import BellIcon from './icons/BellIcon.vue';
import SettingIcon from './icons/SettingIcon.vue';
import QuestionIcon from './icons/QuestionIcon.vue';
import ManuIcon from './icons/ManuIcon.vue';
import CarretDown from './icons/CarretDown.vue';
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
            <div class="searchManu">
                <div class="search">
                    <Search />
                    <input type="text" placeholder="Search anything" />
                </div>
                <div class="settingIcons">
                    <BellIcon />
                    <SettingIcon />
                    <QuestionIcon />
                </div>
                <div class="manuIcon">
                    <ManuIcon />
                </div>
                <div class="avatar">
                    <img src="../assets/avatar.png" alt="avatar" />
                </div>
            </div>
        </div>

        <div class="counting">
            <div class="tasks firstTask">
                <p>Total project <span class="greenText">
                        <CarretUp /> 2
                    </span></p>
                <h1 class="boldNumber">7</h1>
            </div>
            <div class="tasks">
                <p>Total Tasks<span class="greenText">
                        <CarretUp />4
                    </span></p>
                <h1 class="boldNumber">49</h1>
            </div>
            <div class="tasks">
                <p>Assigned Tasks <span class="redText">
                        <CarretDown />3
                    </span></p>
                <h1 class="boldNumber">12</h1>
            </div>
            <div class="tasks">
                <p>Total project <span class="greenText">
                        <CarretUp />1
                    </span></p>
                <h1 class="boldNumber">6</h1>
            </div>
            <div class="tasks lastTask">
                <p>Total project <span class="greenText">
                        <CarretUp />2
                    </span></p>
                <h1 class="boldNumber">3</h1>
            </div>
        </div>

        <div class="main">
            <div class="subnav">
                <div class="subNavBar">
                    <div class="userIcons">
                        <img src="../assets/AD.png" class="AD" alt="user" />
                        <img src="../assets/user.png" alt="user" />
                        <img src="../assets/user+.png" alt="user" />
                    </div>
                    <div class="subCategory">
                        <select name="category">
                            <option>Status Category</option>
                        </select>
                    </div>
                    <div class="workSpace">
                        <select name="workspace">
                            <option>Workspaces</option>
                        </select>
                    </div>
                    <div class="quickFilter">
                        <select name="workspace">
                            <option>Quik Filter</option>
                        </select>
                    </div>
                </div>
                <div class="viewSettings">
                    <img src="../assets/viewsetting.png" alt="user" />
                    <p>View Settings</p>
                </div>
            </div>
            <div class="horizontalLine"></div>
            <div class="tableContainer">
                <table>
                    <thead>
                        <tr>
                            <th></th>
                            <th>JAN</th>
                            <th>FEB</th>
                            <th>MAR</th>
                        </tr>
                    </thead>
                    <tbody>
                        <tr>
                            <td>
                                <div class="sideHead">
                                    <p>+My Hive</p>
                                    <div class="allUsers">
                                        <img src="../assets/AD.png" class="AD" alt="user" />
                                        <img src="../assets/user.png" alt="user" />
                                        <img src="../assets/user+.png" alt="user" />
                                    </div>
                                </div>
                            </td>
                            <td colspan="2">
                                <div class="graph1"></div>
                            </td>
                        </tr>
                        <tr>
                            <td>
                                <div class="sideHead">
                                    <p>+Bomjaour</p>
                                    <div class="allUsers">
                                        <img src="../assets/AD.png" class="AD" alt="user" />
                                        <img src="../assets/user.png" alt="user" />
                                        <img src="../assets/user+.png" alt="user" />
                                    </div>
                                </div>
                            </td>
                            <td colspan="3">
                                <div class="graph2"></div>
                            </td>
                        </tr>
                        <tr>
                            <td>
                                <div class="sideHead">
                                    <p>-Candidate</p>
                                    <div class="allUsers">
                                        <img src="../assets/user.png" alt="user" />

                                    </div>
                                </div>
                            </td>
                            <td colspan="3">
                                <div class="graph3"></div>
                            </td>
                        </tr>
                        <tr>
                            <td>
                                <div class="sideHead">
                                    <p>-Milestone1</p>
                                    <div class="allUsers"></div>
                                </div>
                            </td>
                            <td colspan="3">
                                <div class="graph4"></div>
                            </td>
                        </tr>
                        <tr>
                            <td>
                                <div class="sideHead">
                                    <p>Explore</p>
                                    <div class="allUsers"></div>
                                </div>
                            </td>
                            <td colspan="3">
                                <div class="graph5"></div>
                            </td>
                        </tr>
                        <tr>
                            <td>
                                <div class="sideHead">
                                    <p>+Milestone2</p>
                                    <div class="allUsers">
                                        <img src="../assets/user+.png" alt="user" />
                                    </div>
                                </div>
                            </td>
                            <td colspan="3">
                                <div class="graph6"></div>
                            </td>
                        </tr>
                        <tr>
                            <td>
                                <div class="sideHead">
                                    <p>+CMS</p>
                                    <div class="allUsers">
                                        <img src="../assets/user.png" alt="user" />
                                    </div>
                                </div>
                            </td>
                            <td colspan="3">
                                <div class="graph7"></div>
                            </td>
                        </tr>
                        <tr>
                            <td>
                                <div class="sideHead">
                                    <p>+Jobulus</p>
                                    <div class="allUsers">
                                        <img src="../assets/AD.png" class="AD" alt="user" />
                                        <img src="../assets/user.png" alt="user" />
                                        <img src="../assets/user+.png" alt="user" />
                                    </div>
                                </div>
                            </td>
                            <td colspan="3">
                                <div class="graph9"></div>
                            </td>
                        </tr>
                    </tbody>
                </table>
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
    font-size: 1.3rem;
    font-weight: 700;
    margin-left: 5px;
    margin-top: 2px;

}

.logo {
    width: 25.32px;
    height: 35.12px;
    /* gap: 0px; */
    opacity: 0px;

}

.homeLogo {
    width: 8rem;
    height: 30.12px;
    gap: 0px;
    opacity: 0px;

}

.searchManu {
    display: flex;
    justify-content: space-between;
    width: 35vw;
}

.search {
    display: flex;
    align-items: center;
    border: 1px solid #f4f2f2;
    border-radius: 10px;
    padding: 5px;
    width: 20vw;
}

input {
    border: none;
    outline: none;
    width: 100%;
    padding: 5px;
}

.settingIcons {
    display: flex;
    justify-content: space-between;
    align-items: center;
    gap: 10px;
}

.manuIcon {
    display: flex;
    justify-content: center;
    align-items: center;

}

.avatar {
    display: flex;
    justify-content: center;
    align-items: center;
    border: 1px solid #f4f2f2;
    border-radius: 50%;
    width: 40px;
    height: 40px;
}

.avatar img {
    width: 100%;
    border-radius: 50%;
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
    padding: 20px;
    border: collapse;
    border: 1px dashed rgb(234, 228, 228);
    border-top: none;
    border-bottom: none;
}

.firstTask {
    border-left: none;
}
.lastTask {
    border-right: none;
}

.greenText {
    color: #2CC171;
    margin-left: 5px;
}

.redText {
    color: #FF0000;
    margin-left: 5px;
}


.boldNumber {
    font-size: 2rem;
    font-weight: 700;
}

.main {
    border: collapse;
    border: 1px solid rgb(234, 228, 228);
    border-radius: 10px;
    margin-top: 2vh;
    margin-left: 3vw;
    margin-right: 3vw;
    padding: 15px;
}

.subnav {
    display: flex;
    justify-content: space-between;
    align-items: center;
}

.subNavBar {
    display: flex;
    justify-content: space-between;
    /* width: 70%; */
}

.userIcons img {
    width: 30px;
    height: 30px;
    border-radius: 50%;
}

.AD {
    background-color: green;
    padding: 5px;
    position: relative;
    left: 5px;
}

select {
    padding: 5px;
    border: none;
    margin-left: 10px;
}

.viewSettings {
    display: flex;
    justify-content: center;
    align-items: center;
    column-gap: 5px;
    background-color: #F1F2F4;
    padding: 5px;
    border-radius: 10px;
    cursor: pointer;
}

.viewSettings img {
    width: 20px;
    height: 20px;
}

.horizontalLine {
    height: 1px;
    border: collapse;
    border: 1px dotted rgb(234, 228, 228);
    margin-top: 1.5vh;
}

table,
th,
td {
    border: 1px solid black;
    border-collapse: collapse;
}

table {
    width: 100%;
    margin-top: 2vh;

    padding: 10px;
    border: collapse;
    border: 1px solid rgb(234, 228, 228);
    border-radius: 10px;
}

thead {
    width: 100%;
    border: collapse;
    border: 1px solid rgb(234, 228, 228);
}

tbody {
    width: 100%;
    border: collapse;
    border: 1px solid rgb(234, 228, 228);
}

th {
    width: 20vw;
    border: collapse;
    border: 1px solid rgb(234, 228, 228);
}

td {
    width: 20vw;
    border: collapse;
    border: 1px solid rgb(234, 228, 228);
    font-size: small;
    padding: 10px;
    /* display: flex; */
}

tr:nth-child(even) {
    background-color: #F4F8F9;
}

.graph1 {
    width: 20vw;
    height: 3vh;
    background-color: #3CC553;
}

.graph2 {
    width: 50vw;
    height: 3vh;
    background-color: #3CC553;
    text-align: center;
    margin-left: 10vw;
}

.graph3 {
    width: 20vw;
    height: 3vh;
    background-color: #3CC553;
    text-align: center;
    margin-left: 10vw;
}

.graph4 {
    width: 15vw;
    height: 3vh;
    background-color: #3CC553;
    text-align: center;
    margin-left: 10vw;
}

.graph5 {
    width: 10vw;
    height: 3vh;
    background-color: #3CC553;
    text-align: center;
    margin-left: 10vw;
}

.graph6 {
    width: 7vw;
    height: 3vh;
    background-color: #3CC553;
    text-align: center;
    margin-left: 14vw;
}

.graph7 {
    width: 10vw;
    height: 3vh;
    background-color: #3CC553;
    text-align: center;
    margin-left: 18vw;
}

.graph8 {
    width: 15vw;
    height: 3vh;
    background-color: #3CC553;
    text-align: center;
    margin-left: 20vw;
}

.graph9 {
    width: 35vw;
    height: 3vh;
    background-color: #3CC553;
    text-align: center;
    margin-left: 13vw;
}

.allUsers {
    display: flex;
    /* justify-content: center; */
    /* align-items: center; */
}

.sideHead {
    display: flex;
    justify-content: space-between;
    align-items: center;
}

.allUsers img {
    width: 20px;
    height: 20px;
    border-radius: 50%;

}


@media only screen and (max-width: 768px) {
    .navbar {
        flex-direction: column;
        row-gap: 10px;
    }

    .logos {
        width: 90vw;
        justify-content: space-between;
    }

    .searchManu {
        /* flex-direction: column; */
        row-gap: 10px;
        justify-content: center;
        align-items: center;
        flex-wrap: wrap;
        width: 90vw;
        column-gap: 20px;
    }

    .search {
        width: 70vw;
    }

    .counting {
        flex-direction: column;
        row-gap: 10px;
    }

    .tasks {
        width: 100%;
        height: 100%;
        display: flex;
        flex-direction: column;
        justify-content: center;
        padding: 15px;
        border: collapse;
        border: 1px solid rgb(234, 228, 228);
        border-radius: 10px;

    }

    .main {
        margin-top: 2vh;
        /* margin-left: 3vw;
        margin-right: 3vw; */
        padding: 10px;
        width: 100vw;
    }

    .subnav {
        flex-direction: column;
        row-gap: 10px;
    }

    .subNavBar {
        width: 100%;
        /* flex-direction: column; */
        row-gap: 10px;
        flex-wrap: wrap;
        align-items: center;

    }

    .userIcons {
        width: 100%;
        justify-content: space-between;
    }

    .viewSettings {
        width: 100%;
        justify-content: center;
        align-items: center;
    }

    table {
        width: 100%;
        margin-top: 2vh;
        margin-left: -3vw;
        /* margin-right: 5vw; */
        /* padding: 10px; */
        border: collapse;
        border: 1px solid rgb(234, 228, 228);
        border-radius: 10px;
    }


}
</style>