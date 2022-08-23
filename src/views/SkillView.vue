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
        <div class="skill">
            <h2 class="h-skill">SKILLS</h2>
            <hr>
            <div class="bungkus">
                <div class="isi-1">
                    <span>HTML</span>
                    <div class="progress mb-3" style="width: 1015px;">
                        <div class="progress-bar" style="width: 70%; background-color: slategrey;" role="progressbar" aria-valuenow="75" aria-valuemin="0" aria-valuemax="100"></div>
                    </div>
                    <span>CSS</span>
                    <div class="progress mb-3">
                        <div class="progress-bar" style="width: 70%; background-color: slategrey;" role="progressbar" aria-valuenow="75" aria-valuemin="0" aria-valuemax="100"></div>
                    </div>
                    <span>JAVASCRIPT</span>
                    <div class="progress mb-3">
                        <div class="progress-bar" style="width: 30%; background-color: slategrey;" role="progressbar" aria-valuenow="75" aria-valuemin="0" aria-valuemax="100"></div>
                    </div>
                    <span>FIGMA</span>
                    <div class="progress mb-3">
                        <div class="progress-bar" style="width: 70%; background-color: slategrey;" role="progressbar" aria-valuenow="75" aria-valuemin="0" aria-valuemax="100"></div>
                    </div>
                    <span>BOOTSTRAP</span>
                    <div class="progress mb-3">
                        <div class="progress-bar" style="width: 70%; background-color: slategrey;" role="progressbar" aria-valuenow="75" aria-valuemin="0" aria-valuemax="100"></div>
                    </div>
                    <span>WORDPRESS</span>
                    <div class="progress mb-3">
                        <div class="progress-bar" style="width: 50%; background-color: slategrey;" role="progressbar" aria-valuenow="75" aria-valuemin="0" aria-valuemax="100"></div>
                    </div>
                    <span>PHP</span>
                    <div class="progress mb-3">
                        <div class="progress-bar" style="width: 20%; background-color: slategrey;" role="progressbar" aria-valuenow="100" aria-valuemin="0" aria-valuemax="100"></div>
                    </div>
                    <span>LARAVEL</span>
                    <div class="progress mb-3">
                        <div class="progress-bar" style="width: 40%; background-color: slategrey;" role="progressbar" aria-valuenow="75" aria-valuemin="0" aria-valuemax="100"></div>
                    </div>
                    <span>MS WORD</span>
                    <div class="progress mb-3">
                        <div class="progress-bar" style="width: 50%; background-color: slategrey;" role="progressbar" aria-valuenow="75" aria-valuemin="0" aria-valuemax="100"></div>
                    </div>
                    <span>MS POWERPOINT</span>
                    <div class="progress mb-3">
                        <div class="progress-bar" style="width: 50%; background-color: slategrey;" role="progressbar" aria-valuenow="75" aria-valuemin="0" aria-valuemax="100"></div>
                    </div>
                    
                </div>
                <div class="persentase">
                    
                </div>
            </div>
        </div>
    </div>
</template>

<style>
    .skill{
        text-align: center;
        margin-top: 50px;
        padding: 50px;
        background-color: white;
        border-radius: 20px;
        color: black;
        height: 110vh;
    }

    .h-skill{
        font-weight: bold;
        color: #00bd7e;
    }

    .profile{
        border-radius: 15px;
        border: 3px solid white;
        box-shadow: 0px 0px 3px grey;
    }

    .bungkus{
        display: flex;
    }

    .isi-1{
        text-align: left;
    }
</style>