<template>
    <div class="card">
        <img class="qr-code" alt="qr-code image" src="@/assets/image-qr-code.png"/>
        <div class="content">
            <p class="title">Improve your front-end skills by building projects</p>
            <p class="sub-title">Scan the QR code to visit Frontend Mentor and take your coding skills to the next level</p>
        </div>
    </div>
</template>

<style>
    .card{
        display: flex;
        flex-direction: column;
        justify-content: center;
        align-items: center;
        gap: 24px;

        padding: 1em;
        width: 300px;

        background-color: hsl(0, 0%, 100%);
        border-radius: 15px;
    }
    .qr-code{
        width: 100%;
        border-radius: 15px;
    }
    .content{
        display: flex;
        flex-direction: column;
        align-items: center;
        justify-content: center;
        gap: 16px;
        padding: 0 16px 16px 16px;
        text-align: center;
    }
    .title{
        font-weight: bolder;
        font-size: larger;
        color: hsl(218, 44%, 22%);
    }
    .sub-title{
        font-weight: 400;
        font-size: medium;
        color: hsl(220, 15%, 55%);
    }
</style>