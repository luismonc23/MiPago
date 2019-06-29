<template>
  <f7-page>
    <f7-navbar title="Pasajes de autobús" back-link="Back"></f7-navbar>
    <f7-block-title>Pasajes disponible</f7-block-title>
    <f7-card class="card-not" expandable style="height:270px">
      <f7-card-content :padding="false">
        <div class="bg-color-yellow" :style="{height: '270px'}">
          <f7-card-header text-color="black" class="display-block">
            PASAJE NORMAL
            <br/>
            <small :style="{opacity: 0.7}">Autobús</small>
          </f7-card-header>
          <img class="QR" style="margin:auto 94px auto; display:block;" src="https://api.qrserver.com/v1/create-qr-code/?size=150x150&bgcolor=ffcc00&data=413687HGJ">
          <!-- <f7-link card-close color="black" class="card-opened-fade-in" :style="{position: 'absolute', right: '15px', top: '15px'}" icon-f7="close_round_fill"></f7-link> -->
        </div>
        <!-- <div class="card-content-padding">
          <p>Framework7 - is a free and open source HTML mobile framework to develop hybrid mobile apps or web apps with iOS or Android (Material) native look and feel...</p>
        </div> -->
      </f7-card-content>
    </f7-card>
    <f7-card class="card-not" expandable style="height:270px">
      <f7-card-content :padding="false">
        <div class="bg-color-yellow" :style="{height: '270px'}">
          <f7-card-header text-color="black" class="display-block">
            PASAJE NORMAL
            <br/>
            <small :style="{opacity: 0.7}">Autobús</small>
          </f7-card-header>
          <img class="QR" style="margin:auto 94px auto; display:block;" src="https://api.qrserver.com/v1/create-qr-code/?size=150x150&bgcolor=ffcc00&data=498766HGJ">
          <!-- <f7-link card-close color="black" class="card-opened-fade-in" :style="{position: 'absolute', right: '15px', top: '15px'}" icon-f7="close_round_fill"></f7-link> -->
        </div>
        <!-- <div class="card-content-padding">
          <p>Framework7 - is a free and open source HTML mobile framework to develop hybrid mobile apps or web apps with iOS or Android (Material) native look and feel...</p>
        </div> -->
      </f7-card-content>
    </f7-card>
    <f7-card class="card-not" expandable style="height:270px">
      <f7-card-content :padding="false">
        <div class="bg-color-yellow" :style="{height: '270px'}">
          <f7-card-header text-color="black" class="display-block">
            PASAJE NORMAL
            <br/>
            <small :style="{opacity: 0.7}">Autobús</small>
          </f7-card-header>
          <img class="QR" style="margin:auto 94px auto; display:block;" src="https://api.qrserver.com/v1/create-qr-code/?size=150x150&bgcolor=ffcc00&data=434667HGJ">
          <!-- <f7-link card-close color="black" class="card-opened-fade-in" :style="{position: 'absolute', right: '15px', top: '15px'}" icon-f7="close_round_fill"></f7-link> -->
        </div>
        <!-- <div class="card-content-padding">
          <p>Framework7 - is a free and open source HTML mobile framework to develop hybrid mobile apps or web apps with iOS or Android (Material) native look and feel...</p>
        </div> -->
      </f7-card-content>
    </f7-card>
  </f7-page>
</template>

<script>
export default {}
</script>
