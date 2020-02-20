<template>
    <div class="sidebar">
        <router-link to="/">
            <div class="home">
                <img src="../../assets/home.svg" alt="">
            </div>
        </router-link>
        <router-link to="/transfers">
            <div class="back">
                <img src="../../assets/back-arrow.png" alt="">
            </div>
        </router-link>
    </div>
</template>

<script>
export default {
    name: "Sidebar"
}
</script>

<style scoped>
    .sidebar {
        width: 72px;
        height: 1180px;
        background-color: #ffffff;
        float: left;
        margin-left: 0px;
        margin-top: -30px;
    }
    img {
        height: 20px;
        width: 20px;
        margin: 12px auto;
    }
    .home {
        width: 72px;
        height: 48px;
        background-color: #ececec;
        border-right: 3px #6964d9 solid;
    }
    .back {
        width: 72px;
        height: 48px;
        background-color: #ffffff;
    }
</style>