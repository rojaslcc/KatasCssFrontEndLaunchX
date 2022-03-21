<template>
    <div class="d-flex flex-row w-100 min-vh-100 parent">
        <div class="w-50 d-flex flex-column justify-content-center align-items-center mb-5">
            <div class="w-75">
                <h1 class="page-title">Fight Virus With Vaccines</h1>
                <p class="page-description">Let's stop this pandemic by killing the virus with a vaccine, don't let yourself and your family get infected</p>
            </div>
            <div class="d-flex flex-row mt-3">
                <div class="d-flex flex-row align-items-center">
                    <div class="icon-yellow">
                        <i class="fa-solid fa-shield"></i>
                    </div>
                    <span class="icon-description px-3">Best protection</span>
                </div>
                <div class="d-flex flex-row align-items-center">
                    <div class="icon-yellow">
                        <i class="fa-solid fa-star"></i>
                    </div>
                    <span class="icon-description px-3">Selected Vaccines</span>
                </div>
            </div>
        </div>
        <div class="w-50 bg-gradient-blue d-flex flex-column justify-content-center align-items-center mb-5">
            <div class="w-100 d-flex flex-column">
                <img src="https://web.larioja.org/landing/vacunacion-gripe/img/pareja-vacunando.png" class="img-fluid" alt="..." />
            </div>
        </div>
        <div class="child shadow d-flex justify-content-around align-items-center">
            <div class="d-flex flex-row">
                <div>
                    <i class="fa-solid fa-location-pin icon-blue mx-2"></i>
                </div>
                <div>
                    <h6>Location</h6>
                    <h4>Jakarta Utara</h4>
                </div>
            </div>
            <div class="d-flex flex-row">
                <div>
                    <i class="fa-solid fa-calendar icon-blue mx-2"></i>
                </div>
                <div>
                    <h6>Date</h6>
                    <h4>08 July 2021</h4>
                </div>
            </div>
            <div class="d-flex flex-row">
                <div>
                    <i class="fa-solid fa-pen icon-blue mx-2"></i>
                </div>
                <div>
                    <h6>Vaccine Type</h6>
                    <h4>Moderna</h4>
                </div>
            </div>
            <div>
                <button class="button-vac px-5 py-3">Submit</button>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    name: 'Header'
}
</script>

<style>

h6 {
    color: #6d7b93;
}

h4 {
    color: #1f3e72;
}

.bg-gradient-blue {
    background: rgb(40,146,229);
    background: linear-gradient(90deg, rgba(40,146,229,1) 0%, rgba(44,77,203,1) 100%, rgba(0,212,255,1) 100%);
}

.parent {
    position: relative;
}

.child {
    position: absolute;
    bottom: 3em;
    width: 70%;
    height: auto;
    padding: 30px;
    background-color: #fcfdfe;
    z-index: 10;
    margin-left: 6em;
}

.page-title {
    font-size: 5em;
    font-weight: bold;
}

.page-description {
    font-size: 1.5em;
    color: #6d7b93;
}

.icon-yellow {
    background-color: #fef9e2;
    color: #fbd011;
    padding: 5px;
    border-radius: 5px;
}

.icon-blue {
    background-color: #e9f1fe;
    color: #3050cd;
    padding: 5px;
    border-radius: 5px;
}

.icon-description {
    color: #1f3e72;
}
</style>