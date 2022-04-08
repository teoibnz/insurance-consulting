<template>
    <div class=' my-process-wrapper'>
        <div class="container w-50 text-center py-5 mt-5">
            <p class="process-text mb-5">HOW IT WORKS IN PRACTICE</p>
            <h1 class="fw-bold mb-5"><span class="process-bg process-text rounded p-2">Process</span> Management </h1>
            <p>We work with innovative methodologies to ensure that the entire reformatting process is done from start to finisch as planned.</p>
        </div>
        <div class="container-fluid my-process-line d-flex justify-content-center">
        </div>
        <div class="container d-flex justify-content-evenly">
            <div class="my-process-step">
                <div class="numbers d-flex justify-content-center align-items-center">1</div>
                <h2 class="me-3">Collection of Information</h2>
                <p class="me-3">Lorem ipsum dolor sit amet consectetur.</p>
            </div>
            <div class="my-process-step">
                <div class="numbers d-flex justify-content-center align-items-center">2</div>
                <h2 class="me-3">Strategic planning</h2>
                <p class="me-3">Lorem ipsum dolor sit amet consectetur.</p>
            </div>
            <div class=" my-process-step">
                <div class="numbers d-flex justify-content-center align-items-center">3</div>
                <h2 class="me-3">Assignment of responsabilities</h2>
                <p class="me-3">Lorem ipsum dolor sit amet consectetur.</p>
            </div>
            <div class="my-process-step">
                <div class="numbers d-flex justify-content-center align-items-center">4</div>
                <h2>Formatting process</h2>
                <p>Lorem ipsum dolor sit amet consectetur.</p>
            </div>
            <div class="my-process-step">
                <div class="numbers d-flex justify-content-center align-items-center">5</div>
                <h2>Continuity formalization</h2>
                <p>Lorem ipsum dolor sit amet consectetur.</p>
            </div>
            
        </div>
    </div>
</template>

<script>
export default {
    name : 'ProcessManagement'
}
</script>

<style scoped lang='scss'>
.my-process-wrapper{
    height: 650px;
}
.process-bg{
        background-color: #cce3de;
        color: #058283;
    }
.process-text{
        color: #058283;
    }

.my-process-line{
    border-top: 5px solid #daeced ;
        
}
.numbers{
            font-size: 1.2rem;
            font-weight: bold;
            width: 50px;
            color: #058283;
            background-color: #cce3de;
            border-radius: 50%;
            height: 50px;
            padding: 1.5rem;
            margin-top: -25px;
            margin-left: 6rem;
            margin-bottom: 3rem;
        }
.my-process-step{
    width: calc(100% / 5);
    text-align: center;
    h2{
        font-size: 1.5rem;
        margin-bottom: 1.5rem;
    }
    p{
        font-size: 0.8rem;
    }
}
</style>