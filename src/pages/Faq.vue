<template>
    <section class="client-sectionclient-section ptb-100" v-bind:class="isGray ? 'gray-light-bg' : ''" >
        <header class="header">
        <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@4.6.1/dist/css/bootstrap.min.css" integrity="sha384-zCbKRCUGaJDkqS1kPbPd7TveP5iyJE0EjAuZQTgFLD2ylzuqKfdKlfG/eSrtxUkn" crossorigin="anonymous">

        <!--start navbar-->
        <nav
            class="navbar navbar-expand-lg fixed-top navbarcss"
            v-bind:class="{
                affix: hasAffix,
                'custom-nav': coloredLogo,
                'bg-transparent': !coloredLogo,
                'white-bg': coloredLogo,
            }"
        >
            <div class="container">
                <a class="navbar-brand" href="/"
                    >
                    <img 
                        src="https://drive.google.com/uc?export=view&id=1yKAcF4MMqaqpSuVOt0emTXvPjzXUj7O3"
                        width="120"
                        alt="asas"
                        class="img-fluid"
                    />
                </a>

                <button
                    class="navbar-toggler"
                    type="button"
                    @click="mobileNavClicked"
                    v-bind:class="{ collapsed: collapsed }"
                >
                    <span class="ti-menu"></span>
                </button>

                <div
                    class="collapse navbar-collapse main-menu h-auto"
                    v-bind:class="{ show: !collapsed }"
                    id="navbarSupportedContent"
                >
                    <ul class="navbar-nav ml-auto">
                        <li class="nav-item dropdown">
                            <router-link to="/#inicio"
                                >Inicio</router-link
                            >
                            
                        </li>
                        <li class="nav-item nav-link page-scroll">
                            <router-link :to="{ path: '/', hash: '#about' }"
                                >¿Por qué nosotros?</router-link
                            >
                        </li>

                        <li class="nav-item">
                            <router-link
                                class="nav-link page-scroll"
                                to="/#pricing"
                                v-scroll-to="'#/pricing'"
                                >Precios</router-link
                            >
                        </li>

                        <li class="nav-item">
                            <router-link to="/#faqs" v-scroll-to="'#/faqs'"
                                >Preguntas</router-link
                            >
                        </li>

                        
                        <li class="nav-item">
                            <router-link
                                class="nav-link page-scroll"
                                to="/#contact"
                                v-scroll-to="'#/contact'"
                                >Contacte con</router-link
                            >
                        </li>
                    </ul>
                </div>
            </div>
        </nav>
        <!--end navbar-->
    </header>

        
        <div class="faq-section mt-5 pt-5" id="faqs">
            <div class="container-fluid text-center">
                <img src="img/responsive-contact.png" class="bg-mv" alt="">
                <div class="row">
                    <div class="col-md-6">
                        <img src="img/faqs-desktop.png" class="img-general-desk mt-5 img-fluid" alt="">
                        <img src="img/faqs-movil.png" class="img-general-mov mt-5 img-fluid" alt="">
                    </div>
                    <div class="col-md-5 text-left" data-v-67d141ea="">
                        <div class="section-title" data-v-67d141ea="">
                            <font style="vertical-align: inherit;">
                                <div class="section-heading mb-5">
                                    <h2> Preguntas </h2>
                                </div>
                            </font>
                    </div> 
                    <div class="items-collapse" data-v-67d141ea="">
                        <details class="collapse-item" data-v-67d141ea="">
                            <summary class="title" data-v-67d141ea="">
                                <font style="vertical-align: inherit;">
                                    <font style="vertical-align: inherit;">
                                        ¿Qué son las coberturas ERT?
                                    </font>
                                </font>
                            </summary>
                            <p class="description" data-v-67d141ea="">
                                <font style="vertical-align: inherit;">
                                    <font style="vertical-align: inherit;">
                                        Lorem ipsum pain sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labor et pain magna aliqua. 
                                    </font>
                                </font>
                            </p>
                        </details>
                        <details class="collapse-item" data-v-67d141ea="">
                            <summary class="title" data-v-67d141ea="">
                                <font style="vertical-align: inherit;">
                                    <font style="vertical-align: inherit;">
                                        ¿Qué sucede si contrato un seguro de auto particular, sin cobertura ERT, y utilizo el vehículo para Uber o DiDi?
                                    </font>
                                </font>
                            </summary>
                            <p class="description" data-v-67d141ea="">
                                <font style="vertical-align: inherit;">
                                    <font style="vertical-align: inherit;">
                                        Lorem ipsum pain sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labor et pain magna aliqua. 
                                    </font>
                                </font>
                            </p>
                        </details>
                        <details class="collapse-item" data-v-67d141ea="">
                            <summary class="title" data-v-67d141ea="">
                                <font style="vertical-align: inherit;">
                                    <font style="vertical-align: inherit;">
                                        ¿Por qué son más caros los seguros ERT normalmente?
                                    </font>
                                </font>
                            </summary>
                            <p class="description" data-v-67d141ea="">
                                <font style="vertical-align: inherit;">
                                    <font style="vertical-align: inherit;">
                                        Lorem ipsum pain sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labor et pain magna aliqua. 
                                    </font>
                                </font>
                            </p>
                        </details>
                        
                        <details class="collapse-item" data-v-67d141ea="">
                            <summary class="title" data-v-67d141ea="">
                                <font style="vertical-align: inherit;">
                                    <font style="vertical-align: inherit;">
                                        ¿Por qué el diseño de Gari-ERT tiene precios más bajos que los otros seguros para Uber?
                                    </font>
                                </font>
                            </summary>
                            <p class="description" data-v-67d141ea="">
                                <font style="vertical-align: inherit;">
                                    <font style="vertical-align: inherit;">
                                        Lorem ipsum pain sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labor et pain magna aliqua. 
                                    </font>
                                </font>
                            </p>
                        </details>
                        <details class="collapse-item" data-v-67d141ea="">
                            <summary class="title" data-v-67d141ea="">
                                <font style="vertical-align: inherit;">
                                    <font style="vertical-align: inherit;">
                                        ¿Cómo funciona el seguro complementario de Gari-ERT en conjunto con el que ya te ofrece Uber?
                                    </font>
                                </font>
                            </summary>
                            <p class="description" data-v-67d141ea="">
                                <font style="vertical-align: inherit;">
                                    <font style="vertical-align: inherit;">
                                        Lorem ipsum pain sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labor et pain magna aliqua. 
                                    </font>
                                </font>
                            </p>
                        </details>
                        <details class="collapse-item" data-v-67d141ea="">
                            <summary class="title" data-v-67d141ea="">
                                <font style="vertical-align: inherit;">
                                    <font style="vertical-align: inherit;">
                                        ¿Cual es el proceso para contratar Gari-ERT?
                                    </font>
                                </font>
                            </summary>
                            <p class="description" data-v-67d141ea="">
                                <font style="vertical-align: inherit;">
                                    <font style="vertical-align: inherit;">
                                        Lorem ipsum pain sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labor et pain magna aliqua. 
                                    </font>
                                </font>
                            </p>
                        </details>
                        <details class="collapse-item" data-v-67d141ea="">
                            <summary class="title" data-v-67d141ea="">
                                <font style="vertical-align: inherit;">
                                    <font style="vertical-align: inherit;">
                                        ¿Qué opciones de pago tengo con Gari?
                                    </font>
                                </font>
                            </summary>
                            <p class="description" data-v-67d141ea="">
                                <font style="vertical-align: inherit;">
                                    <font style="vertical-align: inherit;">
                                        Lorem ipsum pain sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labor et pain magna aliqua. 
                                    </font>
                                </font>
                            </p>
                        </details>
                        <details class="collapse-item" data-v-67d141ea="">
                            <summary class="title" data-v-67d141ea="">
                                <font style="vertical-align: inherit;">
                                    <font style="vertical-align: inherit;">
                                        ¿Qué hago en caso de tener un siniestro?
                                    </font>
                                </font>
                            </summary>
                            <p class="description" data-v-67d141ea="">
                                <font style="vertical-align: inherit;">
                                    <font style="vertical-align: inherit;">
                                        Lorem ipsum pain sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labor et pain magna aliqua. 
                                    </font>
                                </font>
                            </p>
                        </details>
                        <details class="collapse-item" data-v-67d141ea="">
                            <summary class="title" data-v-67d141ea="">
                                <font style="vertical-align: inherit;">
                                    <font style="vertical-align: inherit;">
                                        ¿Cómo funciona el seguro complementario de Gari-ERT en conjunto con el que ya te ofrece Uber?
                                    </font>
                                </font>
                            </summary>
                            <p class="description" data-v-67d141ea="">
                                <img
                                    src="img/Capture.PNG"
                                    alt="client logo"
                                    height="200px"
                                    class="client-img"
                                    style="width: 100%;height: 100%;"
                                />
                            </p>
                        </details>
                        
                        </div> 
                            <!-- <a href="/preguntas-frecuentes" target="_self" class="btn btn-primary-outline rounded-pill" data-v-67d141ea="">
                                <font style="vertical-align: inherit;">
                                    <font style="vertical-align: inherit;">
                                        Ver todas las preguntas
                                    </font>
                                </font>
                            </a> -->
                        </div>
                    </div>
            </div>
        </div>
        <footer class="footer-section">
        <div class="bg-footer-custom footer-top pt-150 pb-5 background-img-2">
            <div class="container">
                <div class="row justify-content-between">
                    <div class="col-lg-3 mb-3 mb-lg-0">
                        <div class="footer-nav-wrap text-white">
                            <img 
                                src="https://drive.google.com/uc?export=view&id=1yKAcF4MMqaqpSuVOt0emTXvPjzXUj7O3"
                                width="120"
                                alt="asas"
                                class="img-fluid"
                            />
                            <p>
                                Gari es una empresa de tecnología y analytics enfocada en seguros. Diseñamos y distribuimos productos de auto.
                            </p>

                            <div class="social-list-wrap">
                                <ul
                                    class="social-list list-inline list-unstyled"
                                >
                                    <li class="list-inline-item">
                                        <a
                                            href="#"
                                            target="_blank"
                                            title="Facebook"
                                            ><span class="ti-facebook"></span
                                        ></a>
                                    </li>
                                    &nbsp;
                                    <li class="list-inline-item">
                                        <a
                                            href="#"
                                            target="_blank"
                                            title="Twitter"
                                            ><span class="ti-twitter"></span
                                        ></a>
                                    </li>
                                    &nbsp;
                                    <li class="list-inline-item">
                                        <a
                                            href="#"
                                            target="_blank"
                                            title="Instagram"
                                            ><span class="ti-instagram"></span
                                        ></a>
                                    </li>
                                    &nbsp;
                                    <li class="list-inline-item">
                                        <a
                                            href="#"
                                            target="_blank"
                                            title="printerst"
                                            ><span class="ti-pinterest"></span
                                        ></a>
                                    </li>
                                </ul>
                            </div>
                        </div>
                    </div>
                    <div class="col-lg-3 ml-auto mb-4 mb-lg-0">
                        <div class="footer-nav-wrap text-white">
                            <h5 class="mb-3 text-white">Others Links</h5>
                            <ul class="list-unstyled">
                                <li class="mb-2"><a href="#">Sobre nosotros</a></li>
                                <li class="mb-2"><a href="#">Contacto</a></li>
                                <li class="mb-2"><a href="#">Precios</a></li>
                                <li class="mb-2">
                                    <a href="#">Política de privacidad</a>
                                </li>
                                <li class="mb-2">
                                    <a href="#">Términos y condiciones</a>
                                </li>
                            </ul>
                        </div>
                    </div>
                    <div class="col-lg-3 ml-auto mb-4 mb-lg-0">
                        <div class="footer-nav-wrap text-white">
                            <h5 class="mb-3 text-white">Forma</h5>
                            <ul class="list-unstyled support-list">
                                <li class="mb-2 d-flex align-items-center">
                                    <span class="ti-location-pin mr-2"></span>
                                    Bosque de Ciruelos 186, Bosque de las Lomas, Miguel Hidalgo, CDMX,  CP 11700

                                </li>
                                <li class="mb-2 d-flex align-items-center">
                                    <span class="ti-mobile mr-2"></span>
                                    <a href="tel:XXX-XXX-XXXX">
                                        XXX-XXX-XXXX</a
                                    >
                                </li>
                                <li class="mb-2 d-flex align-items-center">
                                    <span class="ti-email mr-2"></span
                                    ><a href="mailto:www.gari.mx

">
                                        www.gari.mx

</a
                                    >
                                </li>
                                <!-- <li class="mb-2 d-flex align-items-center">
                                    <span class="ti-world mr-2"></span
                                    ><a href="#"> www.yourdomain.com</a>
                                </li> -->
                            </ul>
                        </div>
                    </div>
                    
                </div>
            </div>
        </div>
        <div class="footer-bottom gray-light-bg pt-4 pb-4">
            <div class="container">
                <div class="row text-center justify-content-center">
                    <div class="col-md-6 col-lg-5">
                        <p class="copyright-text pb-0 mb-0">
                            Derechos de autor © 2022 Todos los derechos reservados por
                        </p>
                    </div>
                </div>
            </div>
        </div>
        
    </footer>
    </section>
    
    

    
</template>

<style scoped>
.navbarcss {
    background-image: linear-gradient(to right, rgba(32, 40, 119, 1), rgba(55, 46, 149, 1), rgba(83, 49, 177, 1), rgba(114, 48, 205, 1), rgba(150, 41, 230, 1)) !important;
}
.img-general-desk{
        display: inherit;
    }
    .img-general-mov{
        display: none;
    }
    .faq-section{
        margin-bottom: 100px;
    }
    .section-title{
        font-family: Jost;
        font-style: normal;
        font-weight: 600;
        font-size: 32px;
        line-height: 40px;
        /* identical to box height, or 125% */

        color: #4A25AA;
        margin-bottom: 65px;
    }
    .btn-primary-outline{
        /* Primary color */
        width: 245px;
        height: 45px;
        border: 1px solid #F20C49;
        box-sizing: border-box;
        border-radius: 34px;
        margin-top: 20px;
        color: #F20C49;
    }
    .items-collapse .collapse-item {
        --sp-sm: 1.8rem;
        --sp-md: 25px;
         width: 100%;
        
        margin: 0 auto;
        border-radius: 4px;
        background: rgba(192, 190, 240, 0.2);
        transition: box-shadow 250ms;
        will-change: box-shadow;
        overflow: hidden;
        margin-bottom: 20px;
        /* font-family: Jost; */
        font-family: -apple-system,BlinkMacSystemFont,"Segoe UI",Roboto,"Helvetica Neue",Arial,"Noto Sans","Liberation Sans",sans-serif,"Apple Color Emoji","Segoe UI Emoji","Segoe UI Symbol","Noto Color Emoji";
        font-weight: 500;
    }
    .items-collapse .collapse-item .title {
        position: relative;
        padding: var(--sp-md);
        font-weight: 500;
        font-size: 16px;
        line-height: 23px;
        user-select: none;
        cursor: pointer;
    }
    .items-collapse .collapse-item .title::after {
        content: "→";
        position: absolute;
        right: var(--sp-md);
        top: 50%;
        transform: translateY(-50%);
    }
    .items-collapse .collapse-item[open] .title::after {
        content: "↓";
    }
    .items-collapse .collapse-item .description {
        padding: var(--sp-md);
        margin: 0;
        font-size: 14px;
        line-height: 20px;
        background-color: #FFFFFF;
        border: 0.1rem solid #fafafa;
    }
    .items-collapse .collapse-item .description:not(:first-of-type) {
        padding-top: 0;
    }
    .bg-mv{
        display: none;
    }
    @media (max-width: 576px) { 
        .bg-mv{
            display: initial;
            position: absolute;
            margin-top: -225px;
            right: 0px;
        }
        .faq-section{
            margin-top: -270px;
        }
    }
    .bg-footer-custom {
    background: url("../assets/img/footer-bg.png") no-repeat center top /
        cover !important;
}
</style>



























<script>
// import carousel from "vue-owl-carousel";
export default {
    name: "Customer",
    // components: { carousel },
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


