<template>
   
    <section
        class="client-section ptb-100"
        v-bind:class="isGray ? 'gray-light-bg' : ''"
    >

        <div class="container">
            
            <div class="row justify-content-center">
                <div class="col-md-8">
                    <div class="section-heading text-center mb-5">
                        <p class="lead">
                            Nuestros seguros están respaldados por una de las mejores aseguradoras de México y han sido aprobados por la Comisión Nacional de Seguros y Fianzas
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
           
            <p class="lead text-center mt-5">
                Tenemos una alianza con Seguros El Águila. Ellos nos ayudan a darte el mejor servicio posible en caso de que tengas un siniestro. Nos apoyamos en su red de más de XXX ajustadores en la república y trabajamos con más de XXX talleres y agencias.

            </p>
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
                        <div class="accordion" id="accordionExample">
                            <div class="card">
                                <div class="card-header" id="headingOne">
                                <h2 class="mb-0">
                                    <button class="btn btn-link btn-block text-left" type="button" data-toggle="collapse" data-target="#collapseOne" aria-expanded="true" aria-controls="collapseOne">
                                    Collapsible Group Item #1
                                    </button>
                                </h2>
                                </div>

                                <div id="collapseOne" class="collapse show" aria-labelledby="headingOne" data-parent="#accordionExample">
                                <div class="card-body">
                                    Some placeholder content for the first accordion panel. This panel is shown by default, thanks to the <code>.show</code> class.
                                </div>
                                </div>
                            </div>
                            <div class="card">
                                <div class="card-header" id="headingTwo">
                                <h2 class="mb-0">
                                    <button class="btn btn-link btn-block text-left collapsed" type="button" data-toggle="collapse" data-target="#collapseTwo" aria-expanded="false" aria-controls="collapseTwo">
                                    Collapsible Group Item #2
                                    </button>
                                </h2>
                                </div>
                                <div id="collapseTwo" class="collapse" aria-labelledby="headingTwo" data-parent="#accordionExample">
                                <div class="card-body">
                                    Some placeholder content for the second accordion panel. This panel is hidden by default.
                                </div>
                                </div>
                            </div>
                            <div class="card">
                                <div class="card-header" id="headingThree">
                                <h2 class="mb-0">
                                    <button class="btn btn-link btn-block text-left collapsed" type="button" data-toggle="collapse" data-target="#collapseThree" aria-expanded="false" aria-controls="collapseThree">
                                    Collapsible Group Item #3
                                    </button>
                                </h2>
                                </div>
                                <div id="collapseThree" class="collapse" aria-labelledby="headingThree" data-parent="#accordionExample">
                                <div class="card-body">
                                    And lastly, the placeholder content for the third and final accordion panel. This panel is hidden by default.
                                </div>
                                </div>
                            </div>
                            </div>
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


