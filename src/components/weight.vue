<template>
  <z-view label="Uw gewicht" label-pos="top">
    <h4>Vul uw gewicht in:</h4>
    <p>
        <input style="width: 50%" v-model="weight"/>
    </p>
    <div slot="extension">
      <z-spot to-view="height" button>
        <i style="color: white" class="fas fa-arrow-right"></i>
      </z-spot>
      <z-spot :angle="90" button>
        <i style="color: white" class="fas fa-sync-alt"></i>
      </z-spot>
      <!--
      <z-spot :angle="-90" button to-view="home">
        <i style="color: white" class="fas fa-home"></i>
      </z-spot>
      -->
    </div>
  </z-view>
</template>

<script>
export default {
  data () {
    return {
      weight: 0
    }
  },
  methods: {
  
  }
}
</script>
