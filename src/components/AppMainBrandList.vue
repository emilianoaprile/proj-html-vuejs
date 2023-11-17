<template>
    <div class="container-lg">
        <section class="brands flex flex-column">

            <div class="brand-list-header flex flex-column align-center">
                <h3 class="brand-list-title">Some Brands We Work With</h3>
                <p class="brand-list-text">Lorem ipsum dolor sit amet consectetur adipisicing elit.</p>
            </div>

            <ul class="brand-list flex flex-between">
                <li class="brand-list-item">
                    <img class="brand-img" src="/img/abstract.png" alt="">
                </li>

                <li class="brand-list-item">
                    <img class="brand-img" src="/img/cglobal.png" alt="">
                </li>

                <li class="brand-list-item">
                    <img class="brand-img" src="/img/next.png" alt="">
                </li>

                <li class="brand-list-item">
                    <img class="brand-img" src="/img/hemisferio.png" alt="">
                </li>

                <li class="brand-list-item">
                    <img class="brand-img" src="/img/spaces.png" alt="">
                </li>

                <li class="brand-list-item">
                    <img class="brand-img" src="/img/digitalbox.png" alt="">
                </li>
            </ul>

        </section>

    </div>
</template>

<style scoped>
.brands {
    padding-top: 100px;
    padding-bottom: 75px;
    gap: 50px;
}

.brand-list-header {
    gap: 20px;
}

.brand-list-title {
    font-size: 44px;
}

.brand-img {
    width: 140px;
}

.brand-list-text {
    font-size: 17px;
}
</style>
