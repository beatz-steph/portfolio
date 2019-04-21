<template>
    <div class="container scrollspy" id="act">
        <ul class="tabs">
            <li class="tab"><a href="#activities">Activities</a></li>
            <li class="tab"><a href="#projects">Projects</a></li>
        </ul>
        <div id="activities">
            <div class="row">
                <div class="col s12 l4">
                    <div class="card">
                        <div class="card-image image-used">
                            <img src="https://pbs.twimg.com/profile_images/1083303099886985222/4vHpZnpa.jpg" alt="" height="230px">
                        </div>
                        <div class="card-content">
                            <span class="card-title">
                                HNG internship
                            </span>
                            <p> During the the course of my siwes 300, i was engage in the HNG internship(5th edition). It was a great experience even though it did not last for a long while</p>
                        </div>
                        <div class="card-action">
                            <a href="https://medium.com/@Akinjiola.B/hng-remote-internship-92d56803e6ac">medium post</a>
                        </div>
                    </div>
                </div>
            <div class="col s12 l4">
                    <div class="card">
                        <div class="card-image">
                            <img src="https://cdn-images-1.medium.com/max/853/1*zJkojKNpFD9HFGPJLCs15Q.jpeg" alt="" height="230px" >
                        </div>
                        <div class="card-content">
                            <span class="card-title">
                                Web developement
                            </span>
                            <p> I got introduced to the various aspects of web developement during the course of my siwes 300. This opened my eyes more web technologies that are coming up</p>
                        </div>
                        <div class="card-action">
                            <a href="https://medium.com/@Akinjiola.B/creating-a-server-on-your-node-application-using-express-js-bbd8940eed4b">medium post</a>
                        </div>
                    </div>
                </div>
                <div class="col s12 l4">
                    <div class="card">
                        <div class="card-image">
                            <img src="https://udemy-images.udemy.com/course/480x270/751094_fb27_2.jpg" alt="" height="230px">
                        </div>
                        <div class="card-content">
                            <span class="card-title">
                                Networking
                            </span>
                            <p> Networking was one of the many things i laid my hands on during the course of my siwes 300. I got proper understanding of soe networking terminologies</p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
        <div id="projects"><div class="row">
            <div class="col s12 l4">
                <div class="card">
                    <div class="card-image seek">
                        <img src="https://seekhostel.com/img/logos/black-logo.png" alt="" >
                    </div>
                    <div class="card-content">
                        <span class="card-title">
                            SeekHostel
                        </span>
                        <p>This is website that enables students find accomodation in schools. This services being render are only currently available within Ile-ife </p>
                    </div>
                    <div class="card-action">
                        <a href="www.seekhostel.com">visit</a>
                    </div>
                </div>
            </div>
            <div class="col s12 l4">
                <div class="card">
                    <div class="card-image">
                        <img src="https://i.imgur.com/t69nu5g.png" alt="" height="230px">
                    </div>
                    <div class="card-content">
                        <span class="card-title">
                            Better life savings
                        </span>
                        <p>This is a savings and loans app to enable easy savings and requesting of loans without collateral and  also offering dynamic saving plans</p>
                    </div>
                </div>
            </div>
            
        </div>
        </div>
    </div>
</template>

<script>
export default {
    name:'Activities'
}
</script>
<style>
.seek{
    height: 230px;
}
</style>
