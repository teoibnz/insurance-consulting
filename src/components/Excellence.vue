<template>
    <div class="container-fluid my-excellence-wrapper">
        <div class="container">
            <div class="row">
                <div class="col-12">
                    <p class="excellence-text">OUR BUSINESS AREAS</p>
                    <h1 class="fw-bold mb-5">Excellence in <span class="excellence-bg p-2">Services</span></h1>
                    <div class="d-flex">                    
                        <p class="col-8">
                        We are leaders in providing consultancy services with a set of cutting-edge technoogies and a team of experienced and renowed professionals. these are some options that you can hire.
                        </p>
                        <form class="d-flex ms-5 ps-5">
                            <button class="btn btn-outline-success mx-4 my-button" type="submit">
                                SEE ALL
                            </button>
                        </form>
                    </div>
                </div>
            </div>
            <div class="row mt-5">
                <div class="col-12 d-flex ">
                    <div class="col-4 my-card d-flex flex-column flex-wrap">
                        <div class="">
                            <i>Icon</i>
                            <i>Icon</i>
                        </div>
                        <h3>Audit & Assurance</h3>
                        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit.</p>
                    </div>
                    <div class="col-4 my-card d-flex flex-column">
                        <div class="">
                            <i>Icon</i>
                            <i>Icon</i>
                        </div>
                        <h3>Financial Advisory</h3>
                        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit.</p>
                    </div>
                    <div class="col-4 my-card d-flex flex-column">
                        <div class="">
                            <i>Icon</i>
                            <i>Icon</i>
                        </div>
                        <h3>Analytics and M&A</h3>
                        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit.</p>
                    </div>
                </div>
            </div>
            <div class="row">
                <div class="col-12 d-flex ">
                    <div class="col-4 my-card d-flex flex-column flex-wrap">
                        <div class="">
                            <i>Icon</i>
                            <i>Icon</i>
                        </div>
                        <h3>Middle Marketing</h3>
                        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit.</p>
                    </div>
                    <div class="col-4 my-card d-flex flex-column">
                        <div class="">
                            <i>Icon</i>
                            <i>Icon</i>
                        </div>
                        <h3>Legal Consulting</h3>
                        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit.</p>
                    </div>
                    <div class="col-4 my-card d-flex flex-column">
                        <div class="">
                            <i>Icon</i>
                            <i>Icon</i>
                        </div>
                        <h3>Regulatory Risk</h3>
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
.my-excellence-wrapper{
    padding-top: 10rem;
    background-color: #eef4ed;
}

.my-button{
        background-color: #048383;
        color: white;
        padding: 0.8rem;
        height: 3rem;
    }
.my-card{
    background-color: white;
    width: calc(100% / 4);
    margin-bottom: 2.5rem;
    margin-right: 3.5rem;
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