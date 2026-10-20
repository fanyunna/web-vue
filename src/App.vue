<template>
  <div id="app">
    <!-- <question-view></question-view> -->
    <router-view></router-view>
  </div>
</template>

<script>
/* import QuestionView from './views/elment/QuestionView.vue'
import UserView  from './views/elment/UserView.vue'  */ 
export default {
  /* components:{ QuestionView}, */
  data(){
    return {
      message:"hello vue",
    };
  },
  methods:{

  },
};
</script>
