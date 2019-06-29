<template>
  <f7-page>
    <f7-navbar title="Pasajes de autobús" back-link="Back"></f7-navbar>
    <f7-block-title>Pasajes disponible</f7-block-title>
    <f7-card expandable>
      <f7-card-content :padding="false">
        <div class="bg-color-yellow" :style="{height: '300px'}">
          <f7-card-header text-color="black" class="display-block">
            Framework7
            <br/>
            <small :style="{opacity: 0.7}">Build Mobile Apps</small>
          </f7-card-header>
          <f7-link card-close color="black" class="card-opened-fade-in" :style="{position: 'absolute', right: '15px', top: '15px'}" icon-f7="close_round_fill"></f7-link>
        </div>
        <div class="card-content-padding">
          <p>Framework7 - is a free and open source HTML mobile framework to develop hybrid mobile apps or web apps with iOS or Android (Material) native look and feel...</p>
        </div>
      </f7-card-content>
    </f7-card>
    <f7-block strong>
      <p>Here is About page!</p>
      <p>You can go <f7-link back>back</f7-link>.</p>
      <p>Mauris posuere sit amet metus id venenatis. Ut ante dolor, tempor nec commodo rutrum, varius at sem. Nullam ac nisi non neque ornare pretium. Nulla mauris mauris, consequat et elementum sit amet, egestas sed orci. In hac habitasse platea dictumst.</p>
      <p>Fusce eros lectus, accumsan eget mi vel, iaculis tincidunt felis. Nulla tincidunt pharetra sagittis. Fusce in felis eros. Nulla sit amet aliquam lorem, et gravida ipsum. Mauris consectetur nisl non sollicitudin tristique. Praesent vitae metus ac quam rhoncus mattis vel et nisi. Aenean aliquet, felis quis dignissim iaculis, lectus quam tincidunt ligula, et venenatis turpis risus sed lorem. Morbi eu metus elit. Ut vel diam dolor.</p>
    </f7-block>
  </f7-page>
</template>

<script>
export default {}
</script>
