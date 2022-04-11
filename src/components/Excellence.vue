<template>
    <div class="container-fluid my-excellence-wrapper">
        <div class="container">
            <div class="row">
                <div class="col-12">
                    <p class="excellence-text mb-4">OUR BUSINESS AREAS</p>
                    <h1 class="fw-bold mb-5">Excellence in <span class="excellence-bg p-2 rounded">Services</span></h1>
                    <div class="d-flex">                    
                        <p class="col-8 m-0">
                        We are leaders in providing consultancy services with a set of cutting-edge technoogies and a team of experienced and renowed professionals. these are some options that you can hire.
                        </p>
                        <form class="d-flex ms-5 ps-5">
                            <button class="btn btn-outline-success ms-5 my-button" type="submit">
                                SEE ALL
                            </button>
                        </form>
                    </div>
                </div>
            </div>
            <div class="row mt-5 d-flex justify-content-center">
                <div class="col-12 d-flex ">
                    <div class="col-4 my-card d-flex flex-column flex-wrap">
                        <div class="px-0 mx-0">
                            <i>Icon</i>
                            <i>Icon</i>
                        </div>
                        <h3 class="p-0 mx-4">Audit & Assurance</h3>
                        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit.</p>
                    </div>
                    <div class="col-4 my-card d-flex flex-column">
                        <div class="px-0 mx-0">
                            <i>Icon</i>
                            <i>Icon</i>
                        </div>
                        <h3 class="p-0 mx-4">Financial Advisory</h3>
                        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit.</p>
                    </div>
                    <div class="col-4 my-card d-flex flex-column">
                        <div class="px-0 mx-0">
                            <i>Icon</i>
                            <i>Icon</i>
                        </div>
                        <h3 class="p-0 mx-4">Analytics and M&A</h3>
                        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit.</p>
                    </div>
                </div>
            </div>
            <div class="row">
                <div class="col-12 d-flex">
                    <div class="col-4 my-card d-flex flex-column flex-wrap">
                        <div class="px-0 mx-0">
                            <i>Icon</i>
                            <i>Icon</i>
                        </div>
                        <h3 class="p-0 mx-4">Middle Marketing</h3>
                        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit.</p>
                    </div>
                    <div class="col-4 my-card d-flex flex-column">
                        <div class="px-0 mx-0">
                            <i>Icon</i>
                            <i>Icon</i>
                        </div>
                        <h3 class="p-0 mx-4">Legal Consulting</h3>
                        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit.</p>
                    </div>
                    <div class="col-4 my-card d-flex flex-column">
                        <div class="px-0 mx-0">
                            <i>Icon</i>
                            <i>Icon</i>
                        </div>
                        <h3 class="p-0 mx-4">Regulatory Risk</h3>
                        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit.</p>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    name : 'IndexExcellence'
}
</script>

<style scoped lang='scss'>

*{
    margin: 0 auto;
}
.my-excellence-wrapper{
    padding-top: 10rem;
    // background-color: #eef4ed;
    background-color: #e0eae8;
}

.my-button{
        background-color: #048383;
        color: white;
        padding: 0.8rem;
        height: 3rem;
    }
.my-card{
    background-color: white;
    margin-bottom: 2.5rem;
    margin-right: 1.5rem;
    border-radius: 4%;
    *{
        padding:1rem 1.5rem 1rem 1.5rem;
    }
    
}
.excellence-bg{
        background-color: #cce3de;
        color: #058283;
    }
.excellence-text{
        color: #058283;
    }
</style>