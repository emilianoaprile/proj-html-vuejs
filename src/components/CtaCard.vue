<template>
    <div class="container-lg">

        <div class="cta-card">
            <div class="card-wrapper flex align-center flex-between">
                <div class="consultant-profile flex align-center">
                    <img class="consultant-profile-img" src="/img/card-profile-img.jpg" alt="">
                    <div class="consultant-info">
                        <h4 class="consultant-name">Richard Madsen</h4>
                        <p class="consultant-job">Marketing Consultant Expert</p>
                    </div>
                </div>

                <h5 class="cta-card-title">
                    Drives Leads and Sales with Avada
                </h5>

                <p class="button btn-light-orange consultant-number">
                    <a href="#">
                        <font-awesome-icon icon="fa-solid fa-phone" /> (555) 802-1234
                    </a>
                </p>
            </div>
        </div>

    </div>
</template>

<style scoped lang="scss">
.cta-card {
    margin-top: 100px;
    margin-bottom: 100px;
    box-shadow: 1px 20px 30px -9px rgba(0, 0, 0, 0.42);
    border-radius: 15px;
    padding: 15px 50px;
}

.cta-card-title {
    font-size: 25px;
}

.consultant-profile {
    gap: 25px;

    .consultant-profile-img {
        height: 71px;
        width: 71px;
        border-radius: 50%;
    }

    .consultant-name {
        font-size: 17px;
    }

    .consultant-job {
        font-size: 13px;
        font-weight: 300;
    }
}
</style>