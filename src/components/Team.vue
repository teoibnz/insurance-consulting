<template>
    
    <div class="container-fluid my-team-wrapper">
        <div class="container">
            <div class="row d-flex">
                <div class="col-8">
                    <p class="pre-title fw-bold my-5">WE LIKE WHAT WE DO</p>
                    <h2 class="fw-bold text-white"><span class="team-bg rounded p-2 text-white">Team</span> of Experts</h2>
                    <p class="text-light my-4">Ethics and integrity are the bases on which our professionals build their careers. they are fundamentals that become daily attitudes.</p>
                    <div class="col-6 d-flex my-team">
                        <div class="col-6 d-flex p-3 flex-wrap text-white" v-for='(element , index) in teamComponent' :key="index">
                            <img :src="require('../assets/img/team-1.jpg')" class="img-fluid col-3" alt="pic of team component">
                            <div class="p-3">
                                <h3>{{element.name}}</h3>
                                <span> {{element.role}}</span>
                            </div>
                        </div>
                    </div>
                </div>
            <div class="col-4">
                <div class="speech rounded p-5 my-3">
                    <h3 class="fw-bold text-white py-3">President Speech</h3>
                    <p>
                        Lorem ipsum dolor, sit amet consectetur adipisicing elit. Perferendis, esse eligendi debitis
                    </p>
                    <p>
                        Lorem ipsum dolor, sit amet consectetur adipisicing elit. Perferendis, esse eligendi debitis
                    </p>
                    <p>
                        Lorem ipsum dolor, sit amet consectetur adipisicing elit. Perferendis, esse eligendi debitis
                    </p>
                    <h5 class="text-white my-4">T.Johnson</h5>
                </div>
            </div>
        </div>
    </div>
    </div>
</template>

<script>
export default {
    name : 'IndexTeams',
    data : function(){
        return {
            teamComponent : [
                {
                    name : 'David Cooper',
                    role : 'CTO & CO-FOUNDER',
                    imgUrl : '../assets/img/team-1.jpg',
                },
                {
                    name : 'Oliver Jones',
                    role : 'CHIEF PROCUREMENT',
                    imgUrl : '../assets/img/team-2.jpg',
                },
                {
                    name : 'Emma Lopez',
                    role : 'CHIEF MARKETING',
                    imgUrl : '../assets/img/team-3.jpg',
                },
                {
                    name : 'T. Johnson',
                    role : 'CEO & PRESIDENT',
                    imgUrl : '../assets/img/team-4.jpg',
                },
            ]
            }
    }
}
</script>


<style scoped lang='scss'>
.team-bg{
        background-color: #043c3c;
        color: #043c3c;
    }

.my-team-wrapper{
    background-color: #121117;
    padding: 5rem;

    h2{
        font-size: 2.5rem;
    }
}

.pre-title{
    color : #058283
}

.my-team{
    width: 100%;
    flex-wrap: wrap;
}

.speech{
    width: 90%;
    background-color: #058283;
    p{
        color: white;
        margin-top: 2rem;
        margin-bottom: 2rem;
    }
}

</style>