<template>
  <div id="posts">
    
    <!-- <SkyView></SkyView> -->
    <article id="postsposts">
        <a href="">
      <div id="postImg">
        <img src="../images/1.jpg" alt="이미지" />
      </div>
      <div id="say">말</div>
    </a>
    </article>




     <article id="postsposts">
         <a href="">
      <div id="postImg">
        <img src="../images/2.jpg" alt="이미지" />
      </div>
      <div id="say">말</div>
      </a>
    </article>
     <article id="postsposts">
         <a href="">
      <div id="postImg">
        <img src="../images/3.jpg" alt="이미지" />
      </div>
      <div id="say">말</div>
      </a>
    </article>
     <article id="postsposts">
      <div id="postImg">
        <img src="../images/4.jpg" alt="이미지" />
      </div>
      <div id="say">말</div>
    </article>
  </div>
</template>

<script>
// import SkyView from './components/SkyView.vue'
export default {
components:{
    //   'SkyView':SkyView


}


};
</script>

<style lang="">
#posts {
  padding: 1em 1em 3em;
  column-count: 2;
  overflow: hidden;
  
  width: 90%;
  margin: 0 auto;
}
#postsposts {
  padding: 2em 0em;
  width: 100%;
      display: inline-block;
}

img {
  width: 100%;
  border-radius: 4px;
  display: block;
  height: auto;
  border-style: none;
}
a{display:block;}
</style>
