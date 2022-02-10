<template>
  <section id="about" class="section-padding about-section">
    <div class="container">
      <div class="row">
        <div class="col sm-6">
          <div class="section_title"><br>
          <div class="section_subtitle">About Me</div>
          <h2 class="section_main_title">I am an Aspiring <strong>Dev</strong></h2>

        </div>
        <div class="about-item">
          <p>
              Lorem ipsum dolor sit amet consectetur adipisicing elit. Ullam fugit officia repellendus,
              praesentium molestias magni cupiditate veritatis in magnam illo blanditiis iusto. 
              Minima est modi ipsum voluptas at, unde fugiat. Lorem ipsum dolor, sit amet consectetur adipisicing elit.
              Assumenda vitae molestiae in. Soluta, voluptatem sunt. Aut ratione animi sapiente iure. Lorem ipsum dolor, sit amet consectetur adipisicing elit.
              Tempore esse dicta veniam, pariatur inventore et odio sint quam vel aliquid.
        </p>
        <p>
          Lorem ipsum dolor, sit amet consectetur adipisicing elit. Earum error voluptatem sint accusamus deserunt iusto officia debitis? Corrupti ea est, 
          facere et aperiam fuga obcaecati nobis nemo veritatis officiis atque.
        </p>
        <div class="hgt-20"></div>
        <div class="home-button"></div><br>
        <a href="#" class="btn-color-background">Download Resume</a>  

        </div>
      </div>
      </div> 
      <div class="col-sm-4 col-sm-offset-2">
        <div class="about-box">
          <div class="box-overlay"></div>
          <a href="https://picsum.photos/id/237/200/300/"></a>
          <img src="" alt="">
          <span class= "sonar-emitter"></span> 
        </div>
      </div>
    </div>
  </section>
  <br>
  <br>
  <br>
  <br>
  <br>
  <br>
</template>
<script>
// @ is an alias to /src
//import  from '@/components/ .vue'

export default {
  name: 'About',
  components: {

  }
}
</script>

<style>
.section_title {

}
.section_subtitle{
  margin-bottom: 7px;
  padding-left: 7px;
  font-size: 16px;
  line-height: 1;
  text-transform: uppercase;
  color:rgb(93, 176, 224);
  font-size: 700;
  font-family: tahoma;
}
.section_main_title {
  margin-top: 0;
  margin-bottom: 37px;
  font-size: 30px;
  line-height: 1.27;
  font-weight: 300;
}
.section_main_title strong { 
  font-weight: 600;
}

.about-box {
  -webkit-box-shadow: 0 0 0 10px rgba(129, 235, 192, 0.883) inset;
  box-shadow: 0 0 0 10px rgba(129, 235, 192, 0.883) inset;
  margin-right: 0;
  margin-top: 0;
  position: relative;
  display: block;
}

.box-overlay {
  position: absolute;
  top: 0;
  left: 0;
  height: 100%;
  width: 100%;
  background-color: rgba(51, 48, 48, 0.657);
  opacity: 0.5;
  z-index: 3;
  transform: translateY(30px)  translateX(-30px);
  -webkit-transform: translateY(30px) translateX(-30px);
  
}

.btn-color-background {
  background-color: transparent;
  border: 1px solid bfa67a;
  border-radius: 2px;
  color: #ffffff;
  cursor: pointer;
  display: inline-block;
  font-size: 14px;
  line-height: 1.42857;
  margin-bottom: 0;
  padding: 7px 20px;
  text-align: center;
}
</style>

