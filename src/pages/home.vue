<template>
  <f7-page :page-content='false'>
    <f7-navbar>
      <f7-nav-left>
        <f7-link icon-if-ios="f7:menu" icon-if-md="material:menu" panel-open="left"></f7-link>
      </f7-nav-left>
      <f7-nav-title>MiPago</f7-nav-title>
      <f7-nav-right>
        <!-- <f7-link icon-if-ios="f7:menu" icon-if-md="material:menu" panel-open="right"></f7-link> -->
      </f7-nav-right>
    </f7-navbar>
    <!-- <f7-toolbar bottom>
      <f7-link>Left Link</f7-link>
      <f7-link>Right Link</f7-link>
    </f7-toolbar> -->

    <f7-toolbar tabbar labels :position="'bottom'">
      <f7-link tab-link="#tab-1" tab-link-active text="Pasajes" icon-f7="qrcode"></f7-link>
      <f7-link tab-link="#tab-2" text="Rutas" icon-ios="material:directions_bus" icon-md="material:directions_bus"></f7-link>
      <f7-link tab-link="#tab-3" text="Recargar" icon-ios="material:attach_money" icon-md="material:attach_money"></f7-link>
      <f7-link tab-link="#tab-4" text="SOS" icon-ios="f7:cloud_fill" icon-aurora="f7:cloud_fill" icon-md="material:file_upload"></f7-link>
    </f7-toolbar>

    <f7-tabs>
      <f7-tab id="tab-1" class="page-content" tab-active>
        <!-- <f7-block strong>
          <p>Pasaje disponible</p>
        </f7-block> -->
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

        <f7-card title="Autobús">
          <f7-card-content :padding="false">
            <f7-list>
              <f7-list-item link="/about/" title="Normal" :badge="2 + 1">
                <f7-icon slot="media" material="airport_shuttle"></f7-icon>
              </f7-list-item>
            </f7-list>
          </f7-card-content>
          <!-- <f7-card-footer>
            <span>January 20, 2015</span>
            <span>5 comments</span>
          </f7-card-footer> -->
        </f7-card>
        <!-- <f7-block-title>Navigation</f7-block-title>
        <f7-list>
          <f7-list-item link="/about/" title="About"></f7-list-item>
          <f7-list-item link="/form/" title="Form"></f7-list-item>
        </f7-list>
        <f7-block-title>Modals</f7-block-title>
        <f7-block strong>
          <f7-row>
            <f7-col width="50">
              <f7-button fill raised popup-open="#popup">Popup</f7-button>
            </f7-col>
            <f7-col width="50">
              <f7-button fill raised login-screen-open="#login-screen">Login Screen</f7-button>
            </f7-col>
          </f7-row>
        </f7-block>
        <f7-block-title>Panels</f7-block-title>
        <f7-block strong>
          <f7-row>
            <f7-col width="50">
              <f7-button fill raised panel-open="left">Left Panel</f7-button>
            </f7-col>
            <f7-col width="50">
              <f7-button fill raised panel-open="right">Right Panel</f7-button>
            </f7-col>
          </f7-row>
        </f7-block>
        <f7-list>
          <f7-list-item link="/dynamic-route/blog/45/post/125/?foo=bar#about" title="Dynamic Route"></f7-list-item>
          <f7-list-item link="/load-something-that-doesnt-exist/" title="Default Route (404)"></f7-list-item>
        </f7-list> -->
      </f7-tab>
      <f7-tab id="tab-2" class="page-content">

      </f7-tab>
      <f7-tab id="tab-3" class="page-content">
        <f7-block-title>Recarga de saldo</f7-block-title>
        <f7-card class="card-not" expandable style="height:270px">
          <f7-card-content :padding="false">
            <div class="bg-color-yellow" :style="{height: '270px'}">
              <f7-card-header text-color="black" class="display-block">
                JUAN M.
                <br/>
                <small :style="{opacity: 0.7}">Normal</small>
              </f7-card-header>
              <img class="QR" style="margin:auto 94px auto; display:block;" src="https://api.qrserver.com/v1/create-qr-code/?size=150x150&bgcolor=ffcc00&data=1231443243324432423413687HGJ">
              <!-- <f7-link card-close color="black" class="card-opened-fade-in" :style="{position: 'absolute', right: '15px', top: '15px'}" icon-f7="close_round_fill"></f7-link> -->
            </div>
            <!-- <div class="card-content-padding">
              <p>Framework7 - is a free and open source HTML mobile framework to develop hybrid mobile apps or web apps with iOS or Android (Material) native look and feel...</p>
            </div> -->
          </f7-card-content>
        </f7-card>
      </f7-tab>
      <f7-tab id="tab-4" class="page-content">
        <f7-block>
          <p>Tab 4 content</p>
        </f7-block>
      </f7-tab>
    </f7-tabs>
  </f7-page>
</template>
<script>
export default {}
</script>
