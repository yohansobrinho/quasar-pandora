<template>
  <q-page class="container scene">
    <a-scene arjs='debugUIEnabled: false;'>
      <a-marker id='frac3' type='pattern' url='statics/marker/1.patt' vidhandler>
         <a-plane src="statics/caixa/1.jpeg" scale="6.3 6.3 6.3" rotation="-90 90 0" position="0 0 -0.8" transparent="true">
          </a-plane>
      </a-marker>
      <a-marker id='frac3' type='pattern' url='statics/marker/2.patt' vidhandler>
         <a-plane src="statics/caixa/2.jpg" scale="6.3 6.3 6.3" rotation="-90 90 0" position="0 0 -0.8" transparent="true">
          </a-plane>
      </a-marker>
      <a-marker id='frac3' type='pattern' url='statics/marker/3.patt' vidhandler>
         <a-plane src="statics/caixa/3.jpg" scale="6.3 6.3 6.3" rotation="-90 90 0" position="0 0 -0.8" transparent="true">
          </a-plane>
      </a-marker>
      <a-marker id='frac3' type='pattern' url='statics/marker/4.patt' vidhandler>
         <a-plane src="statics/caixa/4.jpg" scale="6.3 6.3 6.3" rotation="-90 90 0" position="0 0 -0.8" transparent="true">
          </a-plane>
      </a-marker>
      <a-marker id='frac3' type='pattern' url='statics/marker/5.patt' vidhandler>
         <a-plane src="statics/caixa/5.jpg" scale="6.3 6.3 6.3" rotation="-90 90 0" position="0 0 -0.8" transparent="true">
          </a-plane>
      </a-marker>
      <a-marker id='frac3' type='pattern' url='statics/marker/6.patt' vidhandler>
         <a-plane src="statics/caixa/6.jpg" scale="6.3 6.3 6.3" rotation="-90 90 0" position="0 0 -0.8" transparent="true">
          </a-plane>
      </a-marker>
      <a-marker id='frac3' type='pattern' url='statics/marker/7.patt' vidhandler>
         <a-plane src="statics/caixa/7.jpg" scale="6.3 6.3 6.3" rotation="-90 90 0" position="0 0 -0.8" transparent="true">
          </a-plane>
      </a-marker>
        <a-entity camera></a-entity>
    </a-scene>

  </q-page>
</template>

<script>
export default {
  name: 'Aframe'
}
</script>

<style>
.scene {
    z-index: 100 !important;
}
</style>
