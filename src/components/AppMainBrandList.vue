<template>
    <div class="container-lg">
        <section class="brands flex flex-column">

            <div class="brand-list-header flex flex-column align-center">
                <h2 class="brand-list-title">Some Brands We Work With</h2>
                <p class="brand-list-text">Lorem ipsum dolor sit amet consectetur adipisicing elit.</p>
            </div>

            <ul class="brand-list flex flex-between">
                <li class="brand-list-item">
                    <img class="brand-img" src="/public/img/abstract.png" alt="">
                </li>

                <li class="brand-list-item">
                    <img class="brand-img" src="/public/img/cglobal.png" alt="">
                </li>

                <li class="brand-list-item">
                    <img class="brand-img" src="/public/img/next.png" alt="">
                </li>

                <li class="brand-list-item">
                    <img class="brand-img" src="/public/img/hemisferio.png" alt="">
                </li>

                <li class="brand-list-item">
                    <img class="brand-img" src="/public/img/spaces.png" alt="">
                </li>

                <li class="brand-list-item">
                    <img class="brand-img" src="/public/img/digitalbox.png" alt="">
                </li>
            </ul>

        </section>

    </div>
</template>

<style scoped>
.brands {
    margin-top: 100px;
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
