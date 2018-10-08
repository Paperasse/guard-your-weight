<template>
  <z-view label="Uw lengte" label-pos="top">
    <h4>Uw lengte in cm:</h4>
    <p>
        <input style="width: 50%"/>
    </p>
    <div slot="extension">
      <z-spot button to-view="result">
        BMI?
      </z-spot>
      <z-spot :angle="90" button>
        <i style="color: white" class="fas fa-sync-alt"></i>
      </z-spot>
    </div>
  </z-view>
</template>