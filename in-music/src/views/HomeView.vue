<template>
  <div class="home">
    <header-page></header-page>
    <div class="container-fluid sticky-top sticky-lg-top d-flex p-4 home-view-sticky-header">
      <a class="me-4 text-decoration-none text-dark fw-bold home-view-sticky-header__item" href="#">About</a>
      <a class="me-4 text-decoration-none text-dark fw-bold home-view-sticky-header__item" href="#">Jobs</a>
      <a class="me-4 text-decoration-none text-dark fw-bold home-view-sticky-header__item" href="#">Apprenticeships</a>
    </div>
    <div class="container">
      <div class="welcome-image">
        <img src="../assets/music-2.jpg" alt="">
        <div class="welcome-image-caption">
          <p>INMusic</p>
        </div>
      </div>
    </div>
    <div class="container">
      <div class="description-section">
        <h3 class="description-section-header">We make <a class="description-section-header-link" href="">Live</a>, <a class="description-section-header-link" href="">Push</a> and <a class="description-section-header-link" href="">Link</a> — unique software and hardware for music creation and performance. With these products, our community of users creates amazing things.</h3>
        <p class="description-section-text">INMusic was founded in 1999 and released the first version of Live in 2001. Our products are used by a community of dedicated musicians, sound designers, and artists from across the world.</p>
      </div>
    </div>
    <div class="container">
      <div class="row">
        <div class="col-md-6 col-6 home-view-collage-first">
          <img src="../assets/music-5.jpg" alt="">
        </div>
        <div class="col-md-6 col-6 home-view-collage-second">
          <img src="../assets/music-3.jpg" alt="">
        </div>
      </div>
    </div>
    <div class="container">
      <div class="description-section">
        <h3 class="description-section-header">Making music isn’t easy. It takes time, effort, and learning. But when you’re in the flow, it’s incredibly rewarding.</h3>
        <p class="description-section-text">We feel the same way about making INMusic products. The driving force behind INMusic is our passion for what we make, and the people we make it for.</p>
      </div>
    </div>
    <div class="container">
      <div class="media-section">
        <iframe class="video" width="560" height="315" src="https://www.youtube.com/embed/kUoI5Vv8Bu8" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
        <p class="media-section-info">David Guetta - How to make remixes</p>
      </div>
    </div>
    <div class="container">
      <div class="description-section">
        <h3 class="description-section-header">We are more than 350 people from 30 different countries divided between our headquarters in Berlin and our offices in Los Angeles and Tokyo.</h3>
        <p class="description-section-text">Most of us are active musicians, producers, and DJs, and many of us use Live and Push every day. We come from a wide range of cultural and professional backgrounds. Some of us have PhDs, some are self-taught, and most of us are somewhere in between. What connects us is the shared belief that each of us has the skills and knowledge to contribute to something big: helping to shape the future of music culture.</p>
      </div>
    </div>
    <div class="container-fluid">
      <div class="row">
        <div class="col-md-7 col-7 home-view-collage2-first">
          <img src="../assets/music-5.jpg" alt="">
          <img src="../assets/music-5.jpg" alt="">
        </div>
        <div class="col-md-5 col-5 home-view-collage2-second">
          <img src="../assets/music-3.jpg" alt="">
        </div>
      </div>
    </div>
    <div class="container mt-10">
      <div class="description-section">
        <h3 class="description-section-header">We believe it takes focus to create truly outstanding instruments. We only work on a few products and we strive to make them great.</h3>
        <p class="description-section-text">Rather than having a one-size-fits-all process, we try to give our people what they need to work their magic and grow. We’ve learned that achieving the best results comes from building teams that are richly diverse, and thus able to explore problems from a wider set of perspectives. We don’t always agree with each other, but opinion and debate are valued and openly encouraged.</p>
      </div>
    </div>
    <div class="container">
      <div class="welcome-image">
        <img src="../assets/music-6.jpg" alt="">
      </div>
    </div>
    <div class="container">
      <div class="description-section">
        <h3 class="description-section-header">We’re passionate about what we do, but we’re equally passionate about improving who we are.</h3>
        <p class="description-section-text">We work hard to foster an environment where people can grow both personally and professionally, and we strive to create a wealth of opportunities to learn from and with each other.</p>
        <p class="description-section-text">Alongside an internal training program, employees are actively supported in acquiring new knowledge and skills, and coached on applying these in their daily work. In addition, staff-organized development and music salons are a chance to discuss new technologies, production techniques and best practices.</p>
      </div>
    </div>
    <div class="container">
      <div class="middle-collage-section">
        <div class="row">
          <div class="col-md-6 col-6">
            <img class="middle-collage-section-img-first" src="../assets/music-8.jpg" alt="">
          </div>
          <div class="col-md-6 col-6">
            <img class="middle-collage-section-img-second" src="../assets/music-7.jpg" alt="">
          </div>
        </div>
      </div>
    </div>
    <div class="container">
      <div class="description-section">
        <h3 class="description-section-header">We want our employees to love it here. Since we’re looking for exceptional talent from around the world, we will do everything we can to make your transition as easy as possible.</h3>
        <p class="description-section-text">If you're joining us in Berlin, we'll help with relocation and paperwork. We’ll even provide you with free German or English lessons. Plus, working in Germany means you can expect comprehensive health insurance for you and your family, as well as generous maternity and paternity leave. Office hours are flexible, but it’s not all work; we have several company and team outings throughout the year as well as a variety of fun, informal small-group activities.</p>
      </div>
    </div>
    <footer-page></footer-page>
  </div>
</template>

<script>
import HeaderPage from '../shared/HeaderPage.vue'
import FooterPage from '../shared/FooterPage.vue'

export default {
  name: 'HomeView',
  components: {
    HeaderPage,
    FooterPage
  }
}
</script>

<style>

  .home{
    overflow-x: clip;
  }
  .home-view-sticky-header{
    background-color: rgba(255, 255, 255, 0.5);
  }

  .home-view-sticky-header__item{
    font-size: small;
  }

  .home-view-sticky-header__item:hover{
    color: #ff764d!important;
    font-size: small;
  }


  .welcome-image img{
    width: 100%;
    height: 100%;
    position: relative;
    display: inline-block;
  }

  .welcome-image-caption{
    position: absolute;
    margin-top: -30%;
    left: 50%;
    transform: translate(-50%, -50%);
    color: #ff764d;
    padding: 10px;
    font-size: 72px;
    font-weight: 700;
  }


  .description-section{
    padding: 10%;
  }

  .description-section-header{
    font-weight: 700;
    margin-bottom: 30px;
    color: black;
    
  }

  .description-section-text{
    font-weight: 500;
    color: black;
  }

  .description-section-header-link{
    color: #0000ff;
    text-decoration: none;
  }

  .description-section-header-link:hover{
    color: #0000ff;
    text-decoration: none;
  }

  .home-view-collage-first{
    width: 50%;
    height: 100%;
    position: relative;
    left:8%;
    margin-top: 10%!important;
  }
  
  .home-view-collage-first img{
    width: 100%;
    height: 100%;
  }

  .home-view-collage-second{
    background-color:#fbffa7;
    width: 50%;
    height: 50vw;
  }
  
  .home-view-collage-second img{
    width: 100%;
    height: 100%;
    padding: 25%;
  }

  .media-section-info{
    font-weight: 600;
    color: black;
  }

  .home-view-collage2-first{
    width: 50%;
    height: 50vw;
  }

  .home-view-collage2-first img {
    width: 110%;
    height: 100%;
    padding: 25%;
    background-color: #b6ffc0;
  }

  .home-view-collage2-second{
    width: 50%;
    height: 100%;
    position: relative;
    right:5%;
    margin-top: 15%!important;
  }

  .home-view-collage2-second img {
    width: 100%;
    height: 100%;
    
  }

  .video{
    width: 100%;
    height: 50vw;
  }

  .mt-10{
    margin-top: 15%;
  }

  .middle-collage-section{
    background-color: #d5b3ff;
    padding-right: 10%;
    padding-left: 10%;
  }

  .middle-collage-section-img-first{
    width: 130%;
    height: 40vw;
    position: relative;
    margin-top: 50%;
    left: -45%;
    padding: 10%;
  }

  .middle-collage-section-img-second{
    width: 140%;
    height: 50vw;
    position: relative;
    margin-top: 30%;
    right: -5%;
    padding: 10%;
  }
</style>
