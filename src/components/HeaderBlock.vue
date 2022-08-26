<template>
    <header class="header">
        <div class="logo">
            <a class="logo__link" href="#">
                <img src="../assets/heart.png" alt="logo">
                <span class="logo_name">Lerimpresa</span>
            </a>
        </div>
        <div class="burger-menu">
            <span class="burger-menu_name">Menu</span>
            <span class="burger"></span>
        </div>
    </header>
</template>

<script>

export default {
    
}
</script>

<style scoped>
.header {
    display: flex;
    justify-content: space-between;
    align-items: center;

    margin-bottom: 32px;
}

.logo_name,
.burger-menu_name {
    font-family: 'Montserrat';
    font-style: normal;
    font-weight: 300;
    color: #FF855E;
    font-size: 24px;

    cursor: pointer;
    margin-inline: 14px;

    display: none;
}
.logo__link,.burger{
    transition: all .3s linear;
}
.logo__link:hover>.logo_name{
    display: flex;
}
.burger-menu:hover>.burger-menu_name{
    display: flex;
}

.logo__link,
.burger-menu {
    display: flex;
    align-items: center;
}

.burger{
    display: block;
    position: relative;
    right: 0;

    width: 30px;
    height: 3px;

    background-color: #F0503A;
    border-radius: 4px;
}

.burger::before{
    content: '';
    position: absolute;
    top: 250%;
    right: 0;

    width: 30px;
    height: 3px;

    background-color: #F0503A;
    border-radius: 4px;
}
.burger::after{
    content: '';
    position: absolute;
    top: -270%;
    right: 0;

    width: 30px;
    height: 3px;

    background-color: #F0503A;
    border-radius: 4px;
}


</style>
