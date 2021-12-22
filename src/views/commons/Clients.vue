<template>
   
    <section
        class="client-section ptb-100"
        v-bind:class="isGray ? 'gray-light-bg' : ''"
    >
        <div class="container">
            
            <div class="row justify-content-center">
                <div class="col-md-8">
                    <div class="section-heading text-center mb-5">
                        <h2>Trusted by companies</h2>
                        <p class="lead">
                            Rapidiously morph transparent internal or "organic"
                            sources whereas resource sucking e-business.
                            Conveniently innovate compelling internal.
                        </p>
                    </div>
                </div>
            </div>
            <div class="row align-items-center">
                <div class="col-md-12">
                    <carousel
                        :items="1"
                        :nav="false"
                        :autoplay="true"
                        :dots="true"
                        :loop="true"
                        :margin="15"
                        slideTransition="linear"
                        :autoplayTimeout="4000"
                        :autoplaySpeed="false"
                        :smartSpeed="6000"
                        :responsive="{
                            0: { items: 2 },
                            500: { items: 3 },
                            600: { items: 4 },
                            800: { items: 5 },
                            1200: { items: 6 },
                        }"
                        class="owl-theme clients-carousel dot-indicator owl-loaded owl-drag"
                    >
                        <div class="item single-client">
                            <img
                                src="img/airbnb.png"
                                alt="client logo"
                                class="client-img"
                            />
                        </div>
                        <div class="item single-client">
                            <img
                                src="img/amazon.png"
                                alt="client logo"
                                height="30px"
                                class="client-img"
                            />
                        </div>
                        <div class="item single-client">
                            <img
                                src="img/paypal.png"
                                alt="client logo"
                                height="30px"
                                class="client-img"
                            />
                        </div>
                        <div class="item single-client">
                            <img
                                src="img/stripe.png"
                                alt="client logo"
                                height="30px"
                                class="client-img"
                            />
                        </div>
                        <div class="item single-client">
                            <img
                                src="img/shopbott.png"
                                alt="client logo"
                                height="30px"
                                class="client-img"
                            />
                        </div>
                       
                     
                       
                    
                    </carousel>
                </div>
            </div>
           
        </div>
    


      <section id="features" class="feature-section ptb-100">
        <div class="container">
            <div class="row align-items-center justify-content-between">
                <div class="col-md-4">
                    <div class="download-img">
                        <img
                            src="img/image-14.png"
                            alt="download"
                            class="img-fluid"
                        />
                    </div>
                </div>
                <div class="col-md-7">
                    <div class="feature-contents section-heading">
                        <h2>
                            Share your photos with <br />
                            friends easily
                        </h2>
                        <p>
                            Objectively deliver professional value with diverse
                            web-readiness. Collaboratively transition wireless
                            customer service without goal-oriented catalysts for
                            change. Collaboratively.
                        </p>
                        <p>
                            Uniquely simplify sustainable applications whereas
                            adaptive schemas. Competently brand performance
                            based content and.
                        </p>

                        <ul class="list-inline mt-5">
                            <li class="list-inline-item">
                              
                            </li>
                            &nbsp;
                            <li class="list-inline-item">
                                
                            </li>
                            &nbsp;
                            <li class="list-inline-item">
                               
                            &nbsp;
                            <li class="list-inline-item">
                                
                            </li>
                        </ul>
                    </div>
                </div>
            </div>
        </div>
    </section>
















    </section>
    

    
</template>


























<script>
import carousel from "vue-owl-carousel";
export default {
    name: "Customer",
    components: { carousel },
    props: {
        isGray: {
            type: Boolean,
            default: false,
        },
        paddingTop: {
            type: Boolean,
            default: true,
        },
        paddingBottom: {
            type: Boolean,
            default: true,
        },
    },
};
</script>





<style>
</style>


