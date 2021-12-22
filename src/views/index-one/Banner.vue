<template>
    <section class="hero-section pt-100 background-img banner-1-bg">
        <div class="container">
            <div class="row align-items-center justify-content-between py-5">
                <div class="col-md-7 col-lg-6">
                    <div class="hero-content-left text-white">
                        <h1 class="text-white">
                            <span>Brainstorming for desired perfect
                            Usability</span>
                        </h1>
                        <p class="lead">
                            Our design projects are fresh and simple and will
                            benefit your business greatly. Learn more about our
                            work!
                        </p>

                        <form action="#" method="post" class="subscribe-form">
                            <div class="d-flex align-items-center">
                                <input
                                    type="text"
                                    class="form-control input"
                                    id="email"
                                    name="email"
                                    placeholder="info@yourdomain.com"
                                />
                                <input
                                    type="submit"
                                    class="button btn solid-btn"
                                    id="submit"
                                    value="Subscribe"
                                />
                            </div>
                        </form>

                        <div
                            class="video-promo-content py-4 d-flex align-items-center"
                        >
                            <a
                                href="#"
                                @click="showYouTubeModal"
                                class="popup-youtube video-play-icon-without-bip video-play-icon mr-3"
                                ><span class="ti-control-play"></span
                            ></a>
                            Watch Video Overview
                        </div>
                    </div>
                </div>
                <div class=" site-form col-md-5 col-lg-5">
                    <h3 class="top">Get an estimate in seconds</h3>
                     <div class="row">
    <div class="col-6 sub-heading">
     <h6>Date of birth</h6>
    </div>
    <div class="col-6 sub-heading">
      <h6>Postcode</h6>
    </div>
    </div>


                    <span>
                        <form>
  <div class="form-row">
    
    <div class="col-2">
      <input type="text" class="form-control" placeholder="City">
    </div>
    <div class="col-2">
      <input type="text" class="form-control" placeholder="State">
    </div>
    <div class="col-2">
      <input type="text" class="form-control" placeholder="Zip">
    </div>
    <div class="col-6">
      <input type="text" class="form-control" placeholder="Zip">
    </div>
  </div>
</form>



                    </span>


                     <div class="row">
    <div class="col-12 second-put">
    <h6>Enter your car’s registration number</h6>
     <input type="text" class="form-control" placeholder="Zip">
    </div> </div>
    
     <div class="row">
    <div class="col-12 ">
          <button class="btn">Get my estimate</button>
    </div> </div>
  <div class="row">
    <div class="col-12">
       <p class="para"> <a href="">By continuing you are agreeing to our Privacy Policy. </a> </p>
    </div> </div>

                   
                    

                    
                </div>
            </div>
        </div>
        <div class="bottom-img-absolute">
            <img
                src="img/hero-bg-shape-1.svg"
                alt="wave shape"
                class="img-fluid"
            />
        </div>
        <YTModal
            url="https://www.youtube.com/watch?v=1APwq1df6Mw"
            v-if="showModal"
            @close="showModal = false"
        >
            This is my first modal
        </YTModal>
    </section>
</template>

<script>
import YTModal from "../../components/YTModal";
export default {
    name: "Banner",
    components: { YTModal },
    data: function () {
        return {
            showModal: false,
        };
    },
    methods: {
        showYouTubeModal: function (e) {
            e.preventDefault();
            this.showModal = true;
        },
    },
};
</script>

<style>
.banner-1-bg {
    background: url("../../assets/img/app-hero-bg.jpg") no-repeat center center /
        cover !important;
}
</style>