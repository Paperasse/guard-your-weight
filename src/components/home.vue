<template>
  <z-view label="BMI Calculator" label-pos="top">
    <h4>Welkom</h4>
    <p>
        Bereken uw BMI eenvoudig.<br/>
    </p>
    <div slot="extension">
      <z-spot to-view="weight" button>
        <i class="fas fa-weight"></i>
      </z-spot>
    </div>
  </z-view>
</template>
