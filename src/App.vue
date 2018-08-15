<template>
<div class="content">
  <app-header></app-header>
  <br/>
  <router-view></router-view>
  <app-mid></app-mid>
  <app-footer></app-footer>
</div>
</template>
<script>
import Header from './components/Header.vue';
import Footer from './components/Footer.vue';
import Mid from './components/Mid.vue';

export default {
  
  components: {
    'app-header': Header,
    'app-footer': Footer,
    'app-mid': Mid,
  },
  data() {
    return {
      header: true,
    };
  },
  methods: {
 
  },

};
</script>
