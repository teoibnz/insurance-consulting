<template>
    <div>
        <div class="container-fluid my-company-wrapper p-5">
            <div class="container pt-5">
                <div class="row d-flex text-white pt-4">
                    <div class="col-5 mx-1">
                        <p class="text-company">ABOUT THE NETWORK</p>
                        <h1 class="fw-bold my-5">
                            <span class="company-bg p-2">The</span> Company
                        </h1>
                        <p class="mb-4">
                            Lorem ipsum dolor sit amet consectetur adipisicing elit. Nobis suscipit modi cumque nemo nulla voluptatem aperiam totam molestiae voluptas placeat, iure amet blanditiis illo aut ullam assumenda voluptatum, laboriosam eius.
                        </p>
                        <p>
                            Nobis suscipit modi cumque nemo nulla voluptatem aperiam totam molestiae voluptas placeat, iure amet blanditiis illo aut
                        </p>
                    </div>
                    <div class="col-6 d-flex mx-5 flex-wrap pt-5">
                        <div class="col-6">
                            <h3>Tradition</h3> 
                        </div>
                        <div class="col-6">
                            <h3>Security</h3> 
                        </div>
                        <div class="col-6">
                            <h3>Certificate</h3> 
                        </div>
                        <div class="col-6">
                            <h3>Experties</h3> 
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    name : 'TheCompany'
}
</script>

<style scoped lang='scss'>
    .my-company-wrapper{
        background-color: #121117;
        height: 550px;
    }
    .company-bg{
        background-color: #043c3c;
    }

    .text-company{
        color: #048383
    }
</style>