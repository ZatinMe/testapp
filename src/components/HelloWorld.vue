<template>
  <div class="helloapp">
    
    <!-- <video autoplay muted loop id="myVideo">
      <source src="./roadster-loop-imperial.mp4" type="video/mp4">
    </video> -->

    <iframe id = "myVideo"
    src="https://www.facebook.com/plugins/video.php?height=314&href=https%3A%2F%2Fwww.facebook.com%2FNowThisNews%2Fvideos%2F1360468794338159%2F&mute=0" 
      width="560" 
      height="314" 
      style="border:none;overflow:hidden" 
      scrolling="no" 
      autoplay="true"
      mute = "false"
      frameborder="0" 
      allowfullscreen="true" 
      allow="autoplay; clipboard-write; encrypted-media; picture-in-picture; web-share" >
    </iframe>

    <div class="content">
      <h1>Heading</h1>
      <p>Lorem ipsum...</p>
      <button id="myBtn" onclick="myFunction()">Pause</button>
    </div>

    
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  components : {
  },
}
</script>

<style scoped>
#myVideo {
  position: fixed;
  top: 15%;
  right: 15%;
  bottom: 15%;
  min-width: 70%;
  min-height: 70%;
}

.content {
  position: fixed;
  top: 45%;
  right: 15%;
  bottom: 15%;
  background: rgba(0, 0, 0, 0.5);
  color: #f1f1f1;
  width: 70%;
  padding: 20px;
}

#myBtn {
  width: 200px;
  font-size: 18px;
  padding: 10px;
  border: none;
  background: #000;
  color: #fff;
  cursor: pointer;
}

#myBtn:hover {
  background: #ddd;
  color: black;
}
</style>
