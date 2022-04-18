<template>
    <div>
        <div class="logos-wrapper">
        <h2 class="title-header">Find Best Logos</h2>
        <div class="item-logo">
            <img class="logo" alt="Vue logo" src="../assets/logos/logo-1.png">
        </div>
        <div class="item-logo">
            <img class="logo" alt="Vue logo" src="../assets/logos/logo-2.png">
        </div><div class="item-logo">
            <img class="logo" alt="Vue logo" src="../assets/logos/logo-3.png">
        </div><div class="item-logo">
            <img class="logo" alt="Vue logo" src="../assets/logos/logo-4.png">
        </div><div class="item-logo">
            <img class="logo" alt="Vue logo" src="../assets/logos/logo-5.png">
        </div><div class="item-logo">
            <img class="logo" alt="Vue logo" src="../assets/logos/logo-6.png">
        </div><div class="item-logo">
            <img class="logo" alt="Vue logo" src="../assets/logos/logo-7.png">
        </div><div class="item-logo">
            <img class="logo" alt="Vue logo" src="../assets/logos/logo-8.png">
        </div><div class="item-logo">
            <img class="logo" alt="Vue logo" src="../assets/logos/logo-9.png">
        </div><div class="item-logo">
            <img class="logo" alt="Vue logo" src="../assets/logos/logo-10.png">
        </div>
        </div>
    </div>
</template>

<script>
export default {
    name: 'Logos'
}
</script>

<style scoped>
.title-header {
    margin-bottom: 80px;
}

.logos-wrapper{
    width: 63%;
    overflow: hidden;
    margin: auto;
}

.item-logo {
    float: left;
    margin-right: 20px;
    margin-bottom: 20px;
    width: 150px;
    height: 150px;
}

.item-logo .logo {
    width: 150px;
    height: 150px;
}
</style>
