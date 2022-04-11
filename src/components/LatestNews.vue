<template>
    <div class="container news-wrapper d-flex align-items-center">
        <div class="row">
            <div class="col-12 mt-5">
                    <p class="news-text fw-bold">OUR EDITORIAL CONTENT</p>
                    <h1 class="fw-bold mb-5">Excellence in <span class="news-bg p-2 rounded">Services</span></h1>
                    <div class="d-flex justify-content-between">                    
                        <p class="col-8">
                        Every week we publish content about what is best business world.
                        </p>
                        <form class="d-flex ms-5 ps-5">
                            <button class="btn btn-outline-success my-button" type="submit">
                                SEE ALL
                            </button>
                        </form>
                    </div>
                </div>
                <div class="col-12 d-flex card-container py-5">
                    <div class="col-4 my-card">
                        <img  class="img-fluid rounded" :src="require('../assets/img/news-1.jpg')" alt="">
                    </div>
                    <div class="col-4 my-card">
                        <img  class="img-fluid rounded" :src="require('../assets/img/news-2.jpg')" alt="">
                    </div>
                    <div class="col-4 my-card">
                        <img  class="img-fluid rounded" :src="require('../assets/img/news-3.jpg')" alt="">
                    </div>
                </div>
        </div>        
    </div>
</template>

<script>
export default {
    name : 'LatestNews'
}
</script>

<style scoped lang='scss'>
.news-wrapper{
    height: 400px;
    width: 1500px;
    margin-top: 180px;
    margin-bottom: 180px;
    padding: 3rem;
}

.news-bg{
        background-color: #cce3de;
        color: #058283;
    }
.news-text{
        color: #058283;
    }
.my-button{
        background-color: #048383;
        color: white;
        padding: 0.8rem;
        height: 3rem;
    }

.my-card{
        margin-right: 2rem;
    img{
        height: 350px;
        filter: brightness(60%);
    }
}
</style>