<template>
    <section class="case-studies-section">
        <div class="container-lg">

            <div class="section-wrapper flex flex-column">

                <div class="case-studies-header">
                    <h3 class="case-studies-title">Trusted by Leading Organizations</h3>
                </div>

                <div class="case-studies-cards flex">
                    <div class="case-study-card">

                        <img src="/img/case-studies-1.jpg" alt="">
                        <p class="card-text">
                            How Spaces attracted five millions visitors by improving the content.
                        </p>

                        <h2 class="card-title">200%</h2>
                        <p class="card-subtitle">Higher revenue from digital</p>

                    </div>
                    <div class="case-study-card">
                        <img src="/img/case-studies-2.jpg" alt="">
                        <p class="card-text">
                            Creativity helped Hemisferio to increase their brand reach vertically.
                        </p>

                        <h2 class="card-title">10x</h2>
                        <p class="card-subtitle">Higher revenue from digital</p>
                    </div>
                    <div class="case-study-card">
                        <img src="/img/case-studies-3.jpg" alt="">
                        <p class="card-text">
                            How DigitalBox used AI-powered data insight to boost sales.
                        </p>

                        <h2 class="card-title">3-year</h2>
                        <p class="card-subtitle">Higher revenue from digital</p>
                    </div>

                </div>

                <div class="button btn-orange">
                    <a href="#">Read More Case Studies</a>
                </div>

            </div>





        </div>
    </section>
</template>

<style scoped>
.case-studies-section {
    padding-top: 100px;
    padding-bottom: 100px;
    background-color: #f4f4f6;
}

.case-studies-header .case-studies-title {
    text-align: center;
    font-size: 44px;
    margin-bottom: 100px;
}

.case-studies-cards {
    gap: 50px;
}

.button {
    width: max-content;
    align-self: center;
    margin-top: 80px;
}

.card-text {
    font-size: 22px;
    line-height: 30px;
    margin-bottom: 20px;
}

.case-study-card {
    width: 100%;
}

.case-study-card img {
    border-radius: 10px;
    margin-bottom: 20px;
    width: 100%;
}

.card-title {
    font-size: 44px;
    margin-bottom: 10px;

}

.card-subtitle {
    font-size: 17px;
}
</style>