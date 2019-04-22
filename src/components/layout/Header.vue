<template>
    <header>
        <nav class="nav-wrapper black">
            <div class="container">
                <a href="" class="brand-logo black-text">
                    <img src="https://i.imgur.com/epDgKsx.png" alt="" class="z-depth-2 panda">
                </a>
                <a href="" class="sidenav-trigger" data-target="mobile-menu">
                    <i class="material-icons">menu</i>
                </a>
                <ul class="right hide-on-med-and-down">
                    <li><a href="#skills">Skills</a></li>
                    <li><a href="#act">Activities</a></li>
                    <li><a href="#contact">Contact</a></li>
                    <li><a href="https://www.instagram.com/man_like_neyo/" class="btn-floatin btn-small grey darken-2 tooltipped" data-tooltip='Instagram'>
                        <i class="fab fa-instagram"></i>
                    </a></li>
                    <li><a href="https://web.facebook.com/otenku5" class="btn-floatin btn-small grey darken-2 tooltipped" data-tooltip='Facebook'>
                        <i class="fab fa-facebook"></i>
                    </a></li>
                    <li><a href="https://medium.com/@Akinjiola.B" class="btn-floatin btn-small grey darken-2 tooltipped" data-tooltip='Medium'>
                        <i class="fab fa-medium"></i>
                    </a></li>
                </ul>
                <ul class="sidenav grey lighten-2" id="mobile-menu">
                    <li><a href="#">Skills</a></li>
                    <li><a href="#">Projects</a></li>
                    <li><a href="#">Contact</a></li>
                </ul>
            </div>
        </nav>
        <div class="container"><h2>
            <p class="msg">Hey there</p>
            <p class="msg">I am Akinjiola Babaniyi</p>
            </h2>
        </div>
    </header>
</template>

<script>
export default {
    name:'Header',
   
}
</script>


<style scoped>
header{
    background: url(https://i.imgur.com/kGqeTly.jpg);
    background-size: cover;
    background-position: center;
    min-height: 400px;
}

.msg{
   font-family: 'EB Garamond', serif;
   color:white
}

@media screen  and (max-width: 670px){
    header{
        min-height: 200px;
    }    
}
.panda{
    height: 4rem;
}

</style>
