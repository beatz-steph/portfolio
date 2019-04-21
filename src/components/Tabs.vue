<template>
    <section class="container section" id="services">
      <div class="row">
          <div class="col s12 l6">
              <h2 class="blue-text text-darken-4">
                  Favourite Technologies/Tools
              </h2>
              I have come accross a lot web technologies/tools during my couse of trying to learn how to program and design, here are a few i love and why. 
          </div>
          <div class="col s12 l6">
              <ul class="tabs" id="tabs">
                <li class="tab col s4 blue-text text-darken-4 "><a href="#node">NODE</a></li>
                <li class="tab col s4 blue-text text-darken-4"><a href="#xd">ADOBE XD</a></li>
                <li class="tab col s4 blue-text text-darken-4"><a href="#vue">VUE</a></li>
              </ul>
              <div id="node" class="col s12">
                <p class="flow-text">Node</p>
                Node is a javascript framework for creating server side for any application eitehr web or mobile,
                it is one the best option because all your code is in javasript and dependencies can be installed onto the programme you are creating,
                it also comes with npm(node package manager) that can be used to install many frameworks and packages</div>
          <div id="xd" class="col s12">
              <p class="flow-text">Adobe XD</p>
              Adobe Xd is design tool for mobile and web projects which has a lot of features and it is growing fast in the ui/ux design industry,
              the major things that make me prefer Xd to other tools are :
              <br>
              <br>
              Ability to work offline
              <br>
              Built in prototyping and also collaboration with protopie
              <br>
              No OS restriction
               </div>
          <div id="vue" class="col s12">
              <p class="flow-text">Vue</p>
              I love using Vue for my frontend developemnet, it is light, fast and highly functional. It also a javascript framework which works on principles of components.
              It enbles me to break down my entire frontend into various components and connecting them, rather than writiing over 500 lines of code on a single document and start looking for errors.
               </div>

          </div>
         </div>
    </section>
</template>

<script>
export default {
    name:'Tabs',
}

</script>

<style>
.section{
    padding-top: 4vw;
    padding-bottom: 4vw;
}
.tabs .tab a{
    color: #1a237e
}
.tabs .indicator{
    background-color: #1a237e;
  
}
.tabs .tab a:focus, .tabs .tab a:focus.active{
    background: transparent;
    color: #1a237e
}
</style>
