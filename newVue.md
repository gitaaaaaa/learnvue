## ??
```
var vm = new Vue({
  el:'#app',
  data:{
    message: 'Hello'
  },
  methods:{
    getMessage: function(){
      return this.message
    }
  }
  computed:{
    // ?????getter
  }
});
```
