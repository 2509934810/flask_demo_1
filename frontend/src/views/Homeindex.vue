<template>
  <div>
    <top></top>
    <mid></mid>
    <service></service>
    <foot></foot>
  </div>
</template>

<script>
import top from '@/components/JiaZheng/top.vue'
import mid from '@/components/JiaZheng/mid.vue'
import foot from '@/components/JiaZheng/foot.vue'
import service from '@/components/JiaZheng/service.vue'

// var bottom = {
//   template: '<div><h1>sadsa</h1></div>'
// }

export default {
  name: 'Index1',
  data () {
    return {
      msg: '#'
    }
  },
  components: {
    top,
    mid,
    service,
    foot
  }
}
</script>

<style lang="">
  *{margin: 0; padding: 0;}
a{text-decoration: none;}
ul, ol{list-style: none;}
.container{width:100%; margin:0 auto; position: relative;}
.container-fluid{width: 100%;}
img{display: block;}
h1, h2, h3{ font-size: 16px;}
.clear:after{ content: ''; clear:both; display: block;}

.l{float: left;}
.r{float: right;}
body{background-color: lightyellow;}

#bottom{margin-top: 80px; height: 50px; line-height: 50px; background-color:lightseagreen; position: relative;}
#bottom p {float: left;}
#bottom a {float: right; margin-left: 20px; color:black;}

#top .title{margin: 0 auto; height: 60px; line-height: 60px; width: 400px;}
#top .title p{font-size: 30px;}
#top .MainInfo{width: 100px; position: relative; right: 30px; top: -45px; line-height: 50px;}
#top .MainInfo ul {display: none;}
#top .MainInfo:hover ul{display: block;}
#top .MainInfo li a{display: block; width: 100%; height: 100%; text-align: center;}
#top .MainInfo li:hover {background-color: gray;}
</style>
