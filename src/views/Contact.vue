<template>
    <div>
        <transition name="fade" appear>
            <div class="hello">
                <img src="https://lh3.googleusercontent.com/VV780b0q1cAYToZe414q5zdGCPRECidz_YpNvLBs0tEC2q-ApfqQlT86g8wCsk4NuZ3MXf9HkQlYEXmczt5mjC_yYdJ3QCeAvC-YsoTgB917HlWuhygs37Q8b2vKB8K-mzNxVk8utEM=w2400" class="main-img img-fluid" alt="">
            </div>
        </transition>
        <div class="contact">
            <h1>Contact</h1>
            <h2>LE MONDE VERT</h2>
            <h4>モンドベール</h4><br>
            <p class="info">
                大阪府堺市南区宮山台2-3-1
                <br>
                <br>
                代表　吉田加代
                <br>
                Kayo Yoshida
                <br>
                <span class="mail">
                info@monde-vert.com
                </span><br>
                <a href="https://tol-app.jp/s/pnij33cg0l" class="" target=_blank>ネットでのご予約はこちら</a>
            </p>
        </div>
    </div>
</template>

<style scoped>
.hello{
    height: 120vh;
    width: 100vw;
    position: fixed;
    top: 50px;
    z-index: -3;
}
*{
    color: white;
}
.contact{
    height: 45vh;
    width: 100vw;
    margin: 100px 0;
}
h1{
    font-size: 48px;
    margin-bottom: 40px;
}
h2{
    font-size: 40px;
    margin-bottom: 10px;
}
.info{
    font-size: 18px;
    line-height: 36px;
}
.mail{
    border-bottom: 1px solid white;
}
@media screen and (max-width: 640px) {
    .main-img{
        height:600px;
        object-fit:cover;
    }
}
.fade-enter{
    opacity: 0;
}
.fade-enter-active{
    transition: 2s;
}
.fade-enter-to{
    opacity: 1;
}
.fade-leave{
    opacity: 1;
}
.fade-leave-active{
    transition: 2s;
}
.fade-leave-to{
    opacity: 0;
}
</style>