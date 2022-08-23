<template>
    <div class="footer">
        <h4>Copyright @dwinrynt</h4>
        <ul class="ul-footer">
            <li><img src="@/assets/img/telephone-call (1).png" alt="icon"> 0896 9804 3922</li>
            <li><img src="@/assets/img/email (1).png" alt="icon"> do.we.nuryanto@gmail.com</li>
            <li><img src="@/assets/img/location.png" alt="icon"> Depok, West Java</li>
            <li><img src="@/assets/img/instagram (1).png" alt="icon"> d_nrynt</li>
        </ul>
    </div>
</template>

<script>
    export default {
        name: 'Footer'
    };    
</script>



<style>
    .footer{
        margin-top: 50px;
        padding: 20px;
        height: 20vh;
        text-align: center;
        background-color: #00bd7e;
        color: white;
    }

    .ul-footer{
        margin-top: 30px;
        display: flex;
        justify-content: space-evenly;
    }

    .ul-footer li{
        list-style: none;
    }
</style>