<template>
    <div>
        <div class="container-fluid my-newsletter d-flex align-items-center">
            <div class="container d-flex justify-content-center">
                <div class="row d-flex p-5">
                    <div class="col-6 text-white">
                        <p class="footer-text fw-bold my-5">NEWSLETTER</p>
                        <h1 class="fw-bold my-4"><span class="footer-bg p-2">Know</span> First</h1>
                        <p>
                            Follow closely and receive content about our company and the news of the currente market.
                        </p>
                    </div>
                    <div class="col-6">
                        <form class="d-flex col-8 mt-5">
                            <input class="form-control me-2 mb-3 p-2" type="search" placeholder="Name" aria-label="Name">
                        </form>
                        <form class="d-flex col-8">
                            <input class="form-control me-2 p-2" type="search" placeholder="Email" aria-label="Email">
                        </form>
                        <button class="btn btn-outline-success my-button my-4" type="submit">SUBSCRIBE</button>
                    </div>
                </div>
            </div>
        </div>
        <div class="container-fluid footer-container">
            <div class="container">
                <div class="row d-flex my-bottom-wrapper justify-content-center align-items-center">
                    <div class="col-3 d-flex flex-column">
                        <span>
                            <img src="../assets/img/nexgen-logo.svg" class="my-logo" alt="">
                        </span>
                        <span>A functional HTML Template for Corporate & Business.</span>
                        <span> icon +1 (305) 1234-5678</span>
                        <span>hello@example.com</span>
                        <span> Main Avenue, 987</span>
                        <button class=" col-6 btn btn-outline-success my-4" type="submit">GET IN TOUCH</button>
                    </div>
                    <div class="col-2 footer-card rounded mx-3 p-4">
                        <h3 class="mb-2">About</h3>
                        <ul class="p-0">
                            <li v-for="(element, index) in about" :key="index" class="my-3" > > {{element.item}} </li>
                        </ul>
                    </div>
                    <div class="col-2 footer-card  rounded mx-3 p-4">
                        <h3 class="mb-2">Services</h3>
                        <ul class="p-0">
                            <li v-for="(element, index) in services" :key="index" class="my-3"> > {{element.item}}</li>
                        </ul>
                    </div>
                    <div class="col-2 rounded footer-card mx-3 p-4">
                        <h3 class="mb-2">Support</h3>
                        <ul class="p-0">
                            <li v-for="(element, index) in support" :key="index" class="my-3"> > {{element.item}}</li>
                        </ul>
                    </div>
                </div>
            </div>
        </div>
        <div class="container-fluid bg-black">
            <div class="container">
                <div class="row">
                    <div class="col-12 d-flex justify-content-between p-3 text-white">
                        <p class="ps-5">Enjoy the low price. We are tracking any intention of piracy.</p>
                        <p class="pe-5">2020 NEXGEN is Proudly Powered By <span>Coding</span></p>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    name : 'IndexFooter',
    data : function(){
        return {
            about : [
                {
                    item : 'The Company'
                },
                {
                    item : 'Institutional'
                },
                {
                    item : 'Social & Event'
                },
                {
                    item : 'Innovation'
                },
                {
                    item : 'Environment'
                },
                {
                    item : 'Technology'
                },
            ],
            services : [
                {
                    item : 'Audit & Assurance'
                },
                {
                    item : 'Financial Advisory'
                },
                {
                    item : 'Analytics M&A'
                },
                {
                    item : 'Middle Marketing'
                },
                {
                    item : 'Legal Consulting'
                },
                {
                    item : 'Regulatory Risk'
                },
            ],
            support : [
                {
                    item : 'Responsibility'
                },
                {
                    item : 'Therms of Use'
                },
                {
                    item : 'About Cookies'
                },
                {
                    item : 'Privacy Policy'
                },
                {
                    item : 'Accessibility'
                },
                {
                    item : 'Information'
                },
            ]
        }
    }
}
</script>

<style scoped lang="scss">
.my-newsletter{
    background-image: url("../assets/img/bg-1.jpg");
    background-size: cover;
    background-repeat: no-repeat;
    height: 450px;
}
.footer-bg{
        background-color: #043c3c;
    }
.footer-text{
        color: #058283;
    }

.my-button{
        background-color: #048383;
        color: white;
        padding: 0.8rem;
        height: 3rem;
    }

.my-logo{
        height: 4vh;
    }

.footer-container{
    background-color: #111117;
    color: white;
}
.my-bottom-wrapper{
    height: 600px;
    span{
        margin-bottom: 2rem;
    }
    h3{
            font-weight: bold;
            font-size: 1.5rem;
        }

    .footer-card{
        background-color: #19191f;
    }
    ul li{
        list-style-type: none;
        
    }
}
</style>