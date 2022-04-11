<template>
    <div class="jumbo-container container-fluid p-0">
        <div class="row">
            <div class="col-6">
                
            </div>
            <div class="col-6 d-flex flex-column justify-content-center p-5 mt-5">
                <p class="text-jumbo fw-bold">FUSION & ACQUISITIONS</p>
                <h1 class="my-jumbo-title mb-5 col-3 ">Insurance Consulting</h1>
                <div class="col-6 d-flex flex-row mb-3">
                    <input class="form-control me-2 p-3" type="search" placeholder="Name" aria-label="Search">
                    <input class="form-control me-2 p-3" type="search" placeholder="Email" aria-label="Search">
                </div>
                <div class="col-6 d-flex flex-row">
                    <input class="form-control me-2 p-3" type="search" placeholder="Phone" aria-label="Search">
                    <input class="form-control me-2 p-3" type="search" placeholder="More Info" aria-label="Search">
                </div>
                <div class="d-flex mt-3">
                    <form class="d-flex">
                        <button class="btn btn-outline-success my-button" type="submit">GET IN TOUCH</button>
                    </form>
                    <form class="d-flex">
                        <button class="btn btn-outline-success mx-3 p-2" type="submit">READ MORE</button>
                    </form>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    name : 'IndexJumbo'
}
</script>

<style scoped lang="scss">
@import url('https://fonts.googleapis.com/css2?family=Montserrat:wght@100;200;300;400;500;600;700;800;900&display=swap');

*{
    font-family: 'Montserrat', sans-serif;;
}
.jumbo-container{
    height: 80vh;
    background-image: url(../assets/img/bg-6.jpg);
}
.my-jumbo-img{
    height: 70%;

}
.my-button{
        // background-color: #048383;
        background-color: #048383;
        color: white;
    }
    
.my-jumbo-title{
    font-size: 5rem;
    font-weight: 900;
}
.text-jumbo{
        color: #048383
    }
</style>