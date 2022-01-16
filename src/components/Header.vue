<template>
    <div id="header">
      <div id="header-content">
        <div id="logo-container">
        <img id="logo" src="../assets/image/kkb.png" alt="kkb-event">
        </div>
        <div id="slogan">
            <b style="font-size:20px;">feel the power of light</b>
        </div>
        <div id="nav-container">
            <v-btn class="nav-btn" text>HOME</v-btn>
            <v-btn class="nav-btn" text>LEISTUNGEN</v-btn>
            <v-btn class="nav-btn" text>ÜBER</v-btn>
            <v-btn class="nav-btn" text>IMPRESSIONEN</v-btn>
            <v-btn class="nav-btn" text>VERMIETPOOL</v-btn>
            <v-btn class="nav-btn" text>KONTAKT</v-btn>
        </div>
      </div>
    </div>
</template>


<style>
#header {
    width:100%;
    height:100px;
    background-color:black;
    z-index: 2;
}

#header-content {
    width: 1000px;
    display: inline-block;
}

#logo-container {
    width:200px;
    height:200px;
    background-color:rgba(0, 0, 0, 0.8);
    border-radius: 50%;
}

#logo {
    position: relative;
    top: 15px;
    width:180px;
    height:170px;
    -webkit-filter: invert(1);
    filter: invert(1);
}

#slogan {
    position: relative;
    top: -180px;
    left: -200px;
    color: var(--kkb-green)
}

#nav-container {
    position: relative;
    top: -150px;
    left: 100px;
}

.nav-btn {
    margin-left: 10px;
    margin-right: 10px;
    color: var(--kkb-green)
}

.nav-btn:hover {
    color: yellow;
}

</style>