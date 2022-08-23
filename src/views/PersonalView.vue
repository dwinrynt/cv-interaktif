<script setup>
import Personal from '@/components/Personal.vue'
import Footer from '@/components/Footer.vue'
</script>

<template>
    <div class="container">
        <div class="dataDiri">
            <img class="profile" src="@/assets/img/Profile.png" alt="image" width="170">
            <div class="data">
                <h1 class="nama">Dwi Nuryanto</h1>
                <p class="title">Frontend Web Developer</p>
                <hr width="850px">
                <p class="phoneNumber"><img src="@/assets/img/telephone-call (1).png" alt="icon"> 0896 9804 3922</p>
                <p class="email"> <img src="@/assets/img/email (1).png" alt="icon"> do.we.nuryanto@gmail.com</p>
                <p class="location"> <img src="@/assets/img/location.png" alt="icon"> Depok, Jawa Barat</p>
            </div>
        </div>
        <div class="isi">
            <div class="summary">
                <h3 class="h-summary">SUMMARY</h3>
                <hr>
                <p class="p-summary">
                    I was born in Depok, September 3rd, 2004. I am currently studying at Taruna Bhakti Vocational School Depok. I previously had experience in creating and designing multiple web application. I can work individually or work with a team.
                </p>
            </div>
            <div class="education">
                <h3 class="h-education">EDUCATION</h3>
                <hr>
                <p>Software Engineering</p>
                <p>SMK TARUNA BHAKTI</p>
                <p>2022-2023</p>
            </div>
            <div class="experience">
                <h3 class="h-experience">EXPERIENCE</h3>
                <hr>
                <h4>UI Designer</h4>
                <p>Wedding Card Invitation</p>
                <br>
                <h4>UI Designer</h4>
                <p>Food Delivery App</p>
                <br>
                <h4>Designer & Frontend Developer</h4>
                <p>West Java Sarpras Application</p>
                <br>
                <h4>Fullstack Developer</h4>
                <p>Goods Loan Application</p>
            </div>
            <div class="language">
                <h3 class="h-language">LANGUAGE</h3>
                <hr>
                <p><h5>INDONESIAN</h5></p>
                <p><h5>ENGLISH</h5></p>
            </div>
        </div>
    </div>
</template>

<style >
    .container{
        text-align: center;
        margin-top: 50px;
    }

    .dataDiri{
        display: flex;
        justify-content: left;
        gap: 3rem;
        padding-top: 50px;
    }

    .profile{
        border-radius: 15px;
        border: 3px solid white;
        box-shadow: 0px 0px 3px grey;
    }

    hr{
        margin-top: 10px;
        margin-bottom: 10px;
    }

    .isi{
        background-image: url(@/assets/img/91312.jpg);
        border-radius: 20px;
        margin: 0;
        padding: 0;
        width: 100%;
    }

    .nama, .title, .phoneNumber, .email, .location{
        text-align: left;
    }

    .title{
        color: #00bd7e;
    }

    .summary{
        margin-top: 50px;
        text-align: center;
        color: black;
        padding: 50px;
    }

    .education{
        text-align: center;
        color: black;
        padding: 50px;
    }

    .experience{
        text-align: center;
        color: black;
        padding: 50px;
    }

    .language{
        text-align: center;
        color: black;
        padding: 50px;
    }

    h3{
        font-weight: bold;
    }

    .h-summary, .h-education, .h-experience, .h-language{
        font-weight: bold;
        color: #00bd7e;
    }
</style>

