<template>
    <div class="hello">
        <nav class="navbar navbar-expand-lg navbar-light border-bottom">
            <div class="container-fluid">
                <box-icon name='party' type='solid' animation='tada' ></box-icon>
                <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
                    <span class="navbar-toggler-icon"></span>
                </button>
                <div class="collapse navbar-collapse ms-5" id="navbarNav">
                    <ul class="navbar-nav me-auto">
                        <li class="nav-item">
                            <router-link to="/" class="nav-link">Live</router-link>
                        </li>
                        <li class="nav-item">
                            <a class="nav-link" href="#">Push</a>
                        </li>
                        <li class="nav-item">
                            <a class="nav-link" href="#">Note</a>
                        </li>
                        <li class="nav-item">
                            <a class="nav-link" href="#">Link</a>
                        </li>
                        <li class="nav-item">
                            <a class="nav-link" href="#">Shop</a>
                        </li>
                        <li class="nav-item">
                            <a class="nav-link" href="#">Packs</a>
                        </li>
                        <li class="nav-item">
                            <a class="nav-link" href="#">Help</a>
                        </li>
                        <li class="nav-item" @click='reverseIcon'>
                            <a class="nav-link d-flex nav-collapse-button" data-bs-toggle="collapse" href="#collapseExample" role="button" aria-expanded="false" aria-controls="collapseExample">
                                More <box-icon v-if="!showSecondIcon" name='plus'></box-icon> <box-icon v-else name='minus'></box-icon>
                            </a>
                        </li>
                    </ul>
                    <ul class="navbar-nav">
                        <li class="nav-item">
                            <a class="nav-link" href="#">Try Live for free</a>
                        </li>
                        <li class="nav-item">
                            <a class="nav-link" href="#">Log in or register</a>
                        </li>
                    </ul>
                </div>
            </div>
        </nav>
        <div class="collapse" id="collapseExample">
            <div class="card card-body">
                <h3 class="text-start text-dark">More on INMusic.com :</h3>
                <div class="container-fluid d-flex p-2 home-view-sticky-header mt-3">
                    <a class="me-4 text-decoration-none text-dark fw-bold home-view-sticky-header__item" href="#">Blog</a>
                    <a class="me-4 text-decoration-none text-dark fw-bold home-view-sticky-header__item" href="#">INMusic for the Classroom</a>
                    <a class="me-4 text-decoration-none text-dark fw-bold home-view-sticky-header__item" href="#">INMusic for Colleges and Universities</a>
                    <a class="me-4 text-decoration-none text-dark fw-bold home-view-sticky-header__item" href="#">Certified Training</a>
                    <a class="me-4 text-decoration-none text-dark fw-bold home-view-sticky-header__item" href="#">About INMusic</a>
                    <a class="me-4 text-decoration-none text-dark fw-bold home-view-sticky-header__item" href="#">Jobs</a>
                    <a class="me-4 text-decoration-none text-dark fw-bold home-view-sticky-header__item" href="#">Apprenticeships</a>
                </div>
                <h3 class="text-start text-dark mt-3">More from INMusic :</h3>
                    <div class="row mt-3">
                        <div class="col-md-3">
                            <span class="footer-items fw-bolder">Loop</span>
                            <p class="text-start text-dark">Watch Talks, Performances and Features from Ableton's Summit for Music Makers</p>
                        </div>
                        <div class="col-md-3">
                            <span class="footer-items fw-bolder">Learning Music</span>
                            <p class="text-start text-dark">Learn the fundamentals of music making right in your browser.</p>
                        </div>
                        <div class="col-md-3">
                            <span class="footer-items fw-bolder">Learning Synths</span>
                            <p class="text-start text-dark">Get started with synthesis using a web-based synth and accompanying lessons.</p>
                        </div>
                        <div class="col-md-3">
                            <span class="footer-items fw-bolder">Making Music</span>
                            <p class="text-start text-dark">Some tips from 74 Creative Strategies for Electronic Producers.</p>
                        </div>
                    </div>
            </div>
        </div>
    </div>
  </template>
  
  <script>
  export default {
    data() {
        return {
            showSecondIcon: false
        }
    },
    methods : {
        reverseIcon(){
            this.showSecondIcon = !this.showSecondIcon;
        }
    }
  }
  </script>
  
  <style scoped>
    .nav-collapse-button{
        color: #FF764D!important;
    }

    .footer-items{
        color: black;
        text-align: start;
        font-size: 13px;
        display: flex;
        align-items: center;
    }
  </style>
  