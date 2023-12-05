<script setup>
import { ref } from 'vue'
import * as THREE from 'three'
import {Scene}  from 'three'
import { WebGLRenderer } from 'three';
import { PerspectiveCamera } from 'three';
// console.log('Scene', Scene )
// const scene = new Scene()
// const camera = new THREE.PerspectiveCamera(75, window.innerWidth/window.innerHeight, 0.1, 1000)
// scene.add(camera)

// const renderer = new WebGLRenderer({
//   canvas: document.querySelector('#canvas')
// }
// )
// renderer.setSize(window.innerWidth, window.innerHeight)
// const count = ref(0)
</script>

<template>
  <p>hello</p>

  <canvas ref="referience"/>
  <!-- <h1>{{ msg }}</h1>

  <div class="card">
    <button type="button" @click="count++">count is {{ count }}</button>
    <p>
      Edit
      <code>components/HelloWorld.vue</code> to test HMR
    </p>
  </div>

  <p>
    Check out
    <a href="https://vuejs.org/guide/quick-start.html#local" target="_blank"
      >create-vue</a
    >, the official Vue + Vite starter
  </p>
  <p>
    Install
    <a href="https://github.com/vuejs/language-tools" target="_blank">Volar</a>
    in your IDE for a better DX
  </p>
  <p class="read-the-docs">Click on the Vite and Vue logos to learn more</p> -->
</template>

<style scoped>
.read-the-docs {
  color: #888;
}
</style>
