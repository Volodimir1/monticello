<template>
    <section class="header">
        <div class="header__image">
            <div class="header__image-wrapper">
                <img class="header__image-wrapper-im" src="../images/tu-tram-pham-202263.png" alt="head-img">
                <div class="header__head">
                    <div class="header__head-fl">
                        <div>
                            <img class="header__head-logo" src="../images/Logo.svg" alt="Logo">
                        </div>
                        <ul class="header__head-list">
                            <li class="header__head-list-item">
                            <p>About Us</p>
                            </li>
                            <li class="header__head-list-item">
                            <p>projects</p>
                            </li>
                            <li class="header__head-list-item">
                            <p>news</p>
                            </li>
                            <li class="header__head-list-item">
                            <p>contact</p>
                            </li>
                        </ul>
                        <ul class="header__head-list-soc">
                            <li class="header__head-list-soc-item">
                                <img src="../images/Ellipse_2.svg" alt="Ellipse_2">
                                <p class="header__head-list-soc-item-t"></p>
                            </li>
                            <li class="header__head-list-soc-item">
                                <img src="../images/Ellipse_2.svg" alt="Ellipse_2">
                                <p class="header__head-list-soc-item-t"></p>
                            </li>
                            <li class="header__head-list-soc-item">
                                <img src="../images/Ellipse_2.svg" alt="Ellipse_2">
                                <p class="header__head-list-soc-item-t"></p>
                            </li>
                        </ul>
                    </div>
                </div>
                <div class="header__text">
                    <h1 class="header__text-title">Simple & mordern</h1>
                    <p class="header__text-p">We make the world's beautiful every day</p>
                </div>
            </div>
            
        </div>
    </section>
</template>

<script>
export default {
  name: 'Header',
  props: {
    msg: String
  }
}
</script>

// <style scoped lang="scss">
.header {
    height: 100%;
    width: 100%;
    background-color: #4b4b4b;
    background-image: linear-gradient(45deg, #55b7ff 0%, #7e5aff 100%);
    &__image-wrapper {
        position: relative;
    }
    &__image-wrapper-im {
        width: 100%;
        opacity: 0.6;
    }
    &__head {
        position: absolute;
        width: 100%;
        left: auto;
        top: 5%;
        color: #ffffff;
    }
    &__head-fl {
        display: flex;
        flex-direction: row;
        justify-content: space-around;
    }
    &__head-list {
        position: relative;
        bottom: 15px;
        width: 595px;
        list-style: circle;
        display: flex;
        flex-direction: row;
        justify-content: space-around;
    }
    // &__head-list-item {
    // }
    &__head-list-soc {
        width: 162px;
        list-style: none;
        display: flex;
        flex-direction: row;
        justify-content: space-around;
    }
    &__head-list-soc-item {
        position: relative;
    }
    &__head-list-soc-item-t {
        position: absolute;
        width: 100%;
        left: 35%;
        top: 5%;
    }
    &__text {
        position: absolute;
        width: 100%;
        left: auto;
        top: 35%;
        color: #ffffff;
        text-align: center;
    }
    &__text-title {
        font-family: GothamBlack;
        font-size: 80px;
        font-weight: 700;
        line-height: 22px;
        text-transform: uppercase;
        letter-spacing: 4px;
    }
    &__text-p {
        font-family: GothamBook;
        font-size: 18px;
        font-weight: 400;
        line-height: 22px;
        text-transform: uppercase;
        letter-spacing: 5.4px;
    }
}
</style>
