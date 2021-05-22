---

layout: article
title: Background

---

## Education


<div class="grid">


 <div class="cell cell--12 cell--lg-3">

<div class="card">
  <div class="card__image">
    <img class="image" src="/allen.png"/>
  </div>
  <div class="card__content">
    <div class="card__header">
      <h4>Allen High School</h4>
    </div>
    <p>Graduated 2017 <br> High school diploma</p>
  </div>
</div>

</div>

<div class="cell cell--auto">

</div>


<div class="cell cell--12 cell--lg-3">

  <div class="card">
  <div class="card__image">
    <img class="image" src="/utd.png"/>
  </div>
  <div class="card__content">
    <div class="card__header">
      <h4>UTD</h4>
    </div>
    <p>Graduated 2021 <br> B.S. in Electrical Eng.  </p>
  </div>
</div>

</div>

<div class="cell cell--auto">

</div>


<div class="cell cell--12 cell--lg-3">


<div class="card">
  <div class="card__image">
    <img class="image" src="/tech.png"/>
  </div>
  <div class="card__content">
    <div class="card__header">
      <h4>Georgia Tech</h4>
    </div>
    <p>Expected 2026 <br> Ph.D in Electrical Eng.</p>
  </div>
</div>


</div>


</div>

## Experience

<div class="grid">

<div class="cell cell--12 cell--lg-6">

<div class="item">
  <div class="item__image">
    <img class="image" src="/finisar.png"/>
  </div>
  <div class="item__content">
    <div class="item__header">
      <h4>Failure Analysis Intern</h4>
    </div>
    <div class="item__description">
      <p>May 2019 - August 2019</p>
    </div>
  </div>
</div>

</div>

<div class="cell cell--auto">

</div>


<div class="cell cell--12 cell--lg-6">

<div class="item">
  <div class="item__image">
    <img class="image" src="/nsc.PNG"/>
  </div>
  <div class="item__content">
    <div class="item__header">
      <h4> Undergrad Researcher</h4> 
    </div>
    <div class="item__description">
      <p> <a href = "https://personal.utdallas.edu/~joseph.friedman/">Link </a> <br/>  May 2018 - May 2021</p>
    </div>
  </div>
</div>

</div>



</div>

## Awards

<style>
  .swiper-demo {
    height: 220px;
  }
  .swiper-demo .swiper__slide {
    display: flex;
    align-items: center;
    justify-content: center;
    font-size: 3rem;
    color: #fff;
  }
  .swiper-demo .swiper__slide:nth-child(even) {
    background-color: #ff69b4;
  }
  .swiper-demo .swiper__slide:nth-child(odd) {
    background-color: #2593fc;
  }
  .swiper-demo--dark .swiper__slide:nth-child(even) {
    background-color: #312;
  }
  .swiper-demo--dark .swiper__slide:nth-child(odd) {
    background-color: #123;
  }
  .swiper-demo--image .swiper__slide:nth-child(n) {
    background-color: #000;
  }
</style>


<div class="swiper my-3 swiper-demo swiper-demo--image swiper-demo--3">
  <div class="swiper__wrapper">
    <div class="swiper__slide"><a href="https://enroll.utdallas.edu/freshman/aes/prospective-students/qualifications/"><img class="lightbox-ignore" src="/aes.png"/></a></div>
    <div class="swiper__slide"><a href="https://www.scouting.org/resources/guide-to-advancement/eagle-scout-rank/"><img class="lightbox-ignore" src="/bsa.png"/></a></div>
    <div class="swiper__slide"><a href = "https://grad.gatech.edu/presidents-fellowships/"><img class="lightbox-ignore" src="/techa.png"/></a></div>
  </div>
  <div class="swiper__button swiper__button--prev fas fa-chevron-left"></div>
  <div class="swiper__button swiper__button--next fas fa-chevron-right"></div>
</div>



<script>
  {%- include scripts/lib/swiper.js -%}
  var SOURCES = window.TEXT_VARIABLES.sources;
  window.Lazyload.js(SOURCES.jquery, function() {
    $('.swiper-demo--0').swiper();
    $('.swiper-demo--1').swiper();
    $('.swiper-demo--2').swiper();
    $('.swiper-demo--3').swiper();
    $('.swiper-demo--4').swiper({ animation: false });
  });
</script>

## Resume
