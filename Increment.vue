<template>
    <div>
      <!-- TODO -- add your counter code to src/components/Counter.vue -->
      <span data-testid="counter">{{counter}}</span> 
      <button data-testid="increment" @click="increment"> Increment</button>
      <button data-testid="decrement" @click="decrement"> Decrement</button>
    </div>
  </template>
  
  <script>
  // Note: <script setup> syntax is unsupported
  
  export default {
    data(){
      return {
        counter: 0
      }
    },
    
    methods:{
      increment(){
        this.counter++
      },
      
      decrement(){
        this.counter--
      }
    }
  }
  </script>
  
  <style>
  </style>