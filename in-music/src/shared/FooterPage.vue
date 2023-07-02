<template>
        <div class="container">
            <h1 class="footer-header">INMusic</h1>
            <div class="row p-4">
                <div class="col-md-4 d-flex flex-column">
                    <a class="footer-items text-decoration-none" href="#">Register Live or Push <box-icon name='chevron-right'></box-icon></a>
                    <a class="footer-items text-decoration-none" href="#">About INMusic <box-icon name='chevron-right'></box-icon></a>
                    <a class="footer-items text-decoration-none" href="#">Jobs <box-icon name='chevron-right'></box-icon></a>
                    <div class="text-start mt-2">
                        <a class="me-3" href=""><box-icon name='facebook-circle' type='logo' ></box-icon></a>
                        <a class="me-3" href=""><box-icon name='twitter' type='logo' ></box-icon></a>
                        <a class="me-3" href=""><box-icon name='youtube' type='logo' ></box-icon></a>
                        <a class="me-3" href=""><box-icon name='instagram-alt' type='logo' ></box-icon></a>
                    </div>
                </div>
                <div class="col-md-4 d-flex flex-column">
                    <span class="footer-items fw-bolder">Education</span>
                    <a class="footer-items text-decoration-none" href="#">Offers for students and teachers <box-icon name='chevron-right'></box-icon></a>
                    <a class="footer-items text-decoration-none" href="#">INMusic for the Classroom <box-icon name='chevron-right'></box-icon></a>
                    <a class="footer-items text-decoration-none" href="#">INMusic for Colleges and Universities <box-icon name='chevron-right'></box-icon></a>
                </div>
                <div class="col-md-4 d-flex flex-column">
                    <span class="footer-items fw-bolder">Sign up to our newsletter</span>
                    <p class="footer-items">Enter your email address to stay up to date with the latest offers, tutorials, downloads, surveys and more.</p>
                    <div class="row p-2">
                        <div class="col-md-8 col-8 p-0">
                            <input type="text" aria-label="First name" class="form-control" placeholder="Email Address">
                        </div>
                        <div class="col-md-4 col-4 p-0">
                            <button class="btn btn-primary">Sign up</button>
                        </div>
                    </div>
                </div>
                <div class="row mt-3">
                    <div class="col-md-4">
                        <span class="footer-items fw-bolder">Community</span>
                        <a class="footer-items text-decoration-none" href="#">Find INMusic User Groups <box-icon name='chevron-right'></box-icon></a>
                        <a class="footer-items text-decoration-none" href="#">Find Certified Training <box-icon name='chevron-right'></box-icon></a>
                        <a class="footer-items text-decoration-none" href="#">Become a Certified Trainer <box-icon name='chevron-right'></box-icon></a>
                    </div>
                    <div class="col-md-4">
                        <span class="footer-items fw-bolder">Language and Location</span>
                    <div class="row p-2">
                        <div class="col-md-6 p-0">
                            <select class="form-select footer-select" aria-label="Default select example">
                                <option value="1">English</option>
                                <option value="2">Turkish</option>
                            </select>
                        </div>
                        <div class="col-md-6 p-0">
                            <select class="form-select footer-select" aria-label="Default select example">
                                <option value="1">England</option>
                                <option value="2">Türkiye</option>
                            </select>
                        </div>
                    </div>
                    </div>
                </div>
                <div class="container-fluid d-flex p-2 home-view-sticky-header mt-3">
                    <a class="me-4 text-decoration-none text-dark fw-bold home-view-sticky-header__item" href="#">Contact Us</a>
                    <a class="me-4 text-decoration-none text-dark fw-bold home-view-sticky-header__item" href="#">Press Resources</a>
                    <a class="me-4 text-decoration-none text-dark fw-bold home-view-sticky-header__item" href="#">Legal Info</a>
                    <a class="me-4 text-decoration-none text-dark fw-bold home-view-sticky-header__item" href="#">Privacy Policy</a>
                    <a class="me-4 text-decoration-none text-dark fw-bold home-view-sticky-header__item" href="#">Cookie Settings</a>
                    <a class="me-4 text-decoration-none text-dark fw-bold home-view-sticky-header__item" href="#">Imprint</a>
                </div>
            </div>
        </div>
</template>

<script>
    export default{

    }
</script>

<style scoped>
    .footer-header{
        text-align: left;
        padding: 25px;
        color: black;
        font-size: 72px;
    }
    
    .footer-items{
        color: black;
        text-align: start;
        font-size: 13px;
        display: flex;
        align-items: center;
    }

    .footer-select{
        background-color: #eee;
    }
</style>