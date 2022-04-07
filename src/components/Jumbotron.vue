<template>
    <div class="container-fluid p-0">
        <div class="row">
            <div class="col-6">
                <img :src="require('../assets/img/bg-6.jpg')" class="my-jumbo-img" alt="">
            </div>
            <div class="col-6">
                <p>Fusion /& ACQUISITIONS</p>
                <h1>Insurance Consulting</h1>
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
.my-jumbo-img{
    height: 100%;
}
</style>