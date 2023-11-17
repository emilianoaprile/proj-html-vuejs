<template>
    <div class="card">

        <div class="consultant-info flex flex-column align-center">
            <img class="consultant-profile-img" src="/img/card-profile-img.jpg" alt="">
            <h4 class="consultant-name">Richard Madsen</h4>
            <p class="consultant-job">Marketing Consultant Expert</p>
            <p class="consultant-number"><a href="#"><font-awesome-icon icon="fa-solid fa-phone" /> (555) 802-1234</a></p>
        </div>

        <div class="card-form flex flex-column">
            <input class="card-form-info" type="text" name="" id="" placeholder="Your Name*">
            <input class="card-form-info" type="email" name="" id="" placeholder="Your Email*">
            <input class="card-form-info" type="text" name="" id="" placeholder="Your Phone Number*">
            <input class="button btn-orange btn-card" type="submit" value="Get a Callback">
            <p class="card-form-disclaimer">By submitting my data I agree to be contacted</p>
        </div>

    </div>
</template>

<style scoped>
.card {
    background-color: white;
    border-radius: 15px;
    width: 70%;
    margin: 0 auto;
    padding: 30px;
    margin-bottom: -50px;
    box-shadow: 1px 20px 30px -9px rgba(0, 0, 0, 0.42);
}

.consultant-profile-img {
    height: 81px;
    width: 81px;
    border-radius: 50%;
    margin-bottom: 15px;
}

.consultant-name {
    font-size: 22px;
    font-weight: 500;
    margin-bottom: 15px;
}

.consultant-job {
    font-size: 15px;
    font-weight: 300;
    margin-bottom: 15px;
}

.consultant-number {
    margin-bottom: 15px;
    color: rgb(247, 96, 18);
    ;
}

.card-form {
    gap: 15px;
}

.card-form-info {
    width: 100%;
    line-height: 45px;
    padding-left: 5px;
    margin: 0 auto;
    border-radius: 10px;
    border: unset;
    border: 1px solid grey;
}

.btn-card {
    width: 100%;
    margin: 0 auto;
}

.card-form-disclaimer {
    font-size: 12px;
    color: grey;
    text-align: center;
}
</style>