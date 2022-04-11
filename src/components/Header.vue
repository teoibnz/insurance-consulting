<template>
    <div>
        <div class="col-12 company-contact">
            <div class="container text-white pt-1 d-flex justify-content-between">
                <span>Open Hours - Sat - 9:00 - 18:00</span>
                <div>
                    <span class="me-4">+1 (305) 1234-5678</span>
                    <span>hello@example.com</span>
                </div>

            </div>
        </div>
        <header class="container">
        <div class="row">
            <div class="col">
                <nav class="navbar navbar-expand-lg navbar-light bg-light mt-2">
                    <div class="container-fluid">
                        <img src="../assets/img/nexgen-logo.svg" class="my-logo" alt="">
                        <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
                        <span class="navbar-toggler-icon"></span>
                        </button>
                        <div class="collapse navbar-collapse d-flex justify-content-end" id="navbarSupportedContent">
                            <ul class="navbar-nav mb-2 mb-lg-0 text-end">
                                <li class="nav-item me-4" v-for='(element, index) in navBar' :key="index">
                                <a class="nav-link active" aria-current="page" href="#">{{element.item}}</a>
                                </li>
                            </ul>
                            <form class="d-flex">
                                <button class="btn btn-outline-success mx-3 my-button" type="submit">GET IN TOUCH</button>
                            </form>
                        </div>
                    </div>
                </nav>
            </div>
        </div>
        </header>
    </div>
    

</template>

<script>
export default {
    name : 'IndexHeader',
    data : function(){
        return {
            navBar : [
                {
                    item : 'HOME'
                },
                {
                    item : 'ABOUT'
                },
                {
                    item : 'SERVICES'
                },
                {
                    item : 'PROCESS'
                },
                {
                    item : 'TEAM'
                },
                {
                    item : 'BLOG'
                },
            ]
        }
    }
}
</script>

<style  scoped lang="scss">
    .company-contact{
        background-color: #21333e;
        height: 4vh;
    }
    
    .my-button{
        background-color: #048383;
        color: white;
    }
    .my-logo{
        height: 4vh;
    }
</style>