<template>
    <!-- <section class="section section-lg section-shaped overflow-hidden my-0"> -->
    <section>    
                    <b-carousel id="carousel1"
                                controls
                                indicators>
                        <!-- Text slides with image -->
                        <b-carousel-slide img-src="img/images/A.jpg">
                            <h1>MAKAO</h1>
                        </b-carousel-slide>
                        <b-carousel-slide img-src="img/images/B.jpg">
                            <h1>UN PROJET</h1>
                        </b-carousel-slide>
                        <b-carousel-slide img-src="img/images/C.jpg">
                            <h1>COMMUN</h1>
                        </b-carousel-slide>
                        <b-carousel-slide img-src="img/images/D.jpg">
                            <h1>À CHAQUE ÊTRE VIVANT.</h1>
                        </b-carousel-slide>
                    </b-carousel>
            <p><br></p>
            <b-container class="bv-example-row">                
                <b-row>
                    <b-col cols="12" md="4" class="text-center">
                        <img v-lazy="'img/images/vague.jpg'" alt="Raised circle image"
                            class="img-fluid rounded-circle shadow-lg" style="width: 150px;"><br><br>
                        <h2>DEVELOPPER</h2>
                        <p>Duis mollis, est non commodo luctus, nisi erat porttitor ligula, eget lacinia odio sem nec elit. Cras mattis consectetur purus sit amet fermentum. Fusce dapibus, tellus ac cursus commodo, tortor mauris condimentum nibh.</p>
                        <p><a class="btn btn-primary" href="#" role="button">En savoir plus &raquo;</a></p>                           
                    </b-col>
                    <b-col cols="12" md="4" class="text-center">
                        <img v-lazy="'img/images/terre.jpg'" alt="Raised circle image"
                            class="img-fluid rounded-circle shadow-lg" style="width: 150px;"><br><br>
                        <h2>PROTEGER</h2>
                        <p>Duis mollis, est non commodo luctus, nisi erat porttitor ligula, eget lacinia odio sem nec elit. Cras mattis consectetur purus sit amet fermentum. Fusce dapibus, tellus ac cursus commodo, tortor mauris condimentum nibh.</p>
                        <p><a class="btn btn-info" href="#" role="button">En savoir plus &raquo;</a></p>        
                    </b-col>
                    <b-col cols="12" md="4" class="text-center">
                        <img v-lazy="'img/images/poisson.jpg'" alt="Raised circle image"
                            class="img-fluid rounded-circle shadow-lg" style="width: 150px;"><br><br>
                        <h2>DECOUVRIR</h2>
                        <p>Duis mollis, est non commodo luctus, nisi erat porttitor ligula, eget lacinia odio sem nec elit. Cras mattis consectetur purus sit amet fermentum. Fusce dapibus, tellus ac cursus commodo, tortor mauris condimentum nibh.</p>
                        <p><a class="btn btn-success" href="#" role="button">En savoir plus &raquo;</a></p>                       
                    </b-col><b-container><br></b-container>          
                    <b-col cols="12" md="4" class="text-center">
                        <img v-lazy="'img/images/coeur.jpg'" alt="Raised circle image"
                            class="img-fluid rounded-circle shadow-lg" style="width: 150px;"><br><br>
                        <h2>PARTAGER</h2>
                        <p>Duis mollis, est non commodo luctus, nisi erat porttitor ligula, eget lacinia odio sem nec elit. Cras mattis consectetur purus sit amet fermentum. Fusce dapibus, tellus ac cursus commodo, tortor mauris condimentum nibh.</p>
                        <p><a class="btn btn-danger" href="#" role="button">En savoir plus &raquo;</a></p>                           
                    </b-col>
                    <b-col cols="12" md="4" class="text-center">
                        <img v-lazy="'img/images/clap.jpg'" alt="Raised circle image"
                            class="img-fluid rounded-circle shadow-lg" style="width: 150px;"><br><br>
                        <h2>ACCOMPLIR</h2>
                        <p>Duis mollis, est non commodo luctus, nisi erat porttitor ligula, eget lacinia odio sem nec elit. Cras mattis consectetur purus sit amet fermentum. Fusce dapibus, tellus ac cursus commodo, tortor mauris condimentum nibh.</p>
                        <p><a class="btn btn-warning" href="#" role="button">En savoir plus &raquo;</a></p>        
                    </b-col>
                    <b-col cols="12" md="4" class="text-center">
                        <img v-lazy="'img/images/eau.jpg'" alt="Raised circle image"
                            class="img-fluid rounded-circle shadow-lg" style="width: 150px;"><br><br>
                        <h2>RENCONTRER</h2>
                        <p>Duis mollis, est non commodo luctus, nisi erat porttitor ligula, eget lacinia odio sem nec elit. Cras mattis consectetur purus sit amet fermentum. Fusce dapibus, tellus ac cursus commodo, tortor mauris condimentum nibh.</p>
                        <p><a class="btn btn-default" href="#" role="button">En savoir plus &raquo;</a></p>                       
                    </b-col>              
                </b-row>

                <!-- À propos -->
                <hr class="featurette-divider">
                <div class="row featurette">
                <div class="col-md-7">
                    <h2 class="text-success font-weight-light mb-5 featurette-heading">LEA</h2>
                    <p class="lead">Donec ullamcorper nulla non metus auctor fringilla. Vestibulum id ligula porta felis euismod semper. Praesent commodo cursus magna, vel scelerisque nisl consectetur. Fusce dapibus, tellus ac cursus commodo.</p>
                </div>
                <div class="col-md-5">
                    <img src="img/images/1.jpg" width="100%" height="100%" alt="">
                </div>
                </div>
                <hr class="featurette-divider">        
                <div class="row featurette">
                <div class="col-md-7 order-md-2">
                    <h2 class="text-warning font-weight-light mb-5 featurette-heading">STELLA</h2>
                    <p class="lead">Donec ullamcorper nulla non metus auctor fringilla. Vestibulum id ligula porta felis euismod semper. Praesent commodo cursus magna, vel scelerisque nisl consectetur. Fusce dapibus, tellus ac cursus commodo.</p>
                </div>
                <div class="col-md-5 order-md-1">
                    <img src="img/images/2.jpg" width="100%" height="100%" alt="">
                </div>
                </div>        
                <hr class="featurette-divider">            
                <div class="row featurette">
                <div class="col-md-7">
                    <h2 class="text-danger font-weight-light mb-5 featurette-heading">BLANCHE</h2>
                    <p class="lead">Donec ullamcorper nulla non metus auctor fringilla. Vestibulum id ligula porta felis euismod semper. Praesent commodo cursus magna, vel scelerisque nisl consectetur. Fusce dapibus, tellus ac cursus commodo.</p>
                </div>
                <div class="col-md-5">
                    <img src="img/images/3.jpg" width="100%" height="100%" alt="">
                </div>
                </div>
            </b-container>
            <b-container><br><hr></b-container>

            <!-- video -->
            <h1>En savoir plus</h1>
            <div>
                <b-embed
                    type="iframe"
                    aspect="16by9"
                    src="https://www.youtube.com/embed/7s8IgEiVqog" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen
                ></b-embed>
            </div>
            
            <!-- Le Bocal -->

            <b-container><br><hr></b-container>
            <b-container class="bv-bocal-row">
                <h1 class="text-center-text-success">Le Bocal</h1>               
                <b-row>
                    <b-col cols="12" md="4" class="text-center">
                        <img v-lazy="'img/images/600x600px/Poisson-1a.jpg'" alt="Raised circle image"
                            class="img-fluid rounded " style="width: 300px;"><br><br>
                        <h2>49.99$/an</h2>
                        <p> Magnifique poisson du massif corallien.</p>
                        <p><a class="btn btn-primary" href="#" role="button">Adopter &raquo;</a></p>                           
                    </b-col>
                    <b-col cols="12" md="4" class="text-center">
                        <img v-lazy="'img/images/600x600px/Poisson-2a.jpg'" alt="Raised circle image"
                            class="img-fluid rounded " style="width: 300px;"><br><br>
                        <h2>49.99$/an</h2>
                        <p> Magnifique poisson du massif corallien.</p>
                        <p><a class="btn btn-primary" href="#" role="button">Adopter &raquo;</a></p>                           
                    </b-col>
                    <b-col cols="12" md="4" class="text-center">
                        <img v-lazy="'img/images/600x600px/Poisson-3a.jpg'" alt="Raised circle image"
                            class="img-fluid rounded " style="width: 300px;"><br><br>
                        <h2>49.99$/an</h2>
                        <p> Magnifique poisson du massif corallien.</p>
                        <p><a class="btn btn-primary" href="#" role="button">Adopter &raquo;</a></p>                           
                    </b-col>
                    <b-col cols="12" md="4" class="text-center">
                        <img v-lazy="'img/images/600x600px/Poisson-4a.jpg'" alt="Raised circle image"
                            class="img-fluid rounded " style="width: 300px;"><br><br>
                        <h2>49.99$/an</h2>
                        <p> Magnifique poisson du massif corallien.</p>
                        <p><a class="btn btn-primary" href="#" role="button">Adopter &raquo;</a></p>                           
                    </b-col>
                    <b-col cols="12" md="4" class="text-center">
                        <img v-lazy="'img/images/600x600px/Poisson-5a.jpg'" alt="Raised circle image"
                            class="img-fluid rounded " style="width: 300px;"><br><br>
                        <h2>49.99$/an</h2>
                        <p> Magnifique poisson du massif corallien.</p>
                        <p><a class="btn btn-primary" href="#" role="button">Adopter &raquo;</a></p>                           
                    </b-col>
                    <b-col cols="12" md="4" class="text-center">
                        <img v-lazy="'img/images/600x600px/Poisson-6a.jpg'" alt="Raised circle image"
                            class="img-fluid rounded " style="width: 300px;"><br><br>
                        <h2>49.99$/an</h2>
                        <p> Magnifique poisson du massif corallien.</p>
                        <p><a class="btn btn-primary" href="#" role="button">Adopter &raquo;</a></p>                           
                    </b-col>
                    <b-col cols="12" md="4" class="text-center">
                        <img v-lazy="'img/images/600x600px/Poisson-7a.jpg'" alt="Raised circle image"
                            class="img-fluid rounded " style="width: 300px;"><br><br>
                        <h2>49.99$/an</h2>
                        <p> Magnifique poisson du massif corallien.</p>
                        <p><a class="btn btn-primary" href="#" role="button">Adopter &raquo;</a></p>                           
                    </b-col>
                    <b-col cols="12" md="4" class="text-center">
                        <img v-lazy="'img/images/600x600px/Poisson-8a.jpg'" alt="Raised circle image"
                            class="img-fluid rounded " style="width: 300px;"><br><br>
                        <h2>49.99$/an</h2>
                        <p> Magnifique poisson du massif corallien.</p>
                        <p><a class="btn btn-primary" href="#" role="button">Adopter &raquo;</a></p>                           
                    </b-col>
                    <b-col cols="12" md="4" class="text-center">
                        <img v-lazy="'img/images/600x600px/Poisson-9a.jpg'" alt="Raised circle image"
                            class="img-fluid rounded " style="width: 300px;"><br><br>
                        <h2>49.99$/an</h2>
                        <p> Magnifique poisson du massif corallien.</p>
                        <p><a class="btn btn-primary" href="#" role="button">Adopter &raquo;</a></p>                           
                    </b-col>
                    <b-col cols="12" md="4" class="text-center">
                        <img v-lazy="'img/images/600x600px/Poisson-10a.jpg'" alt="Raised circle image"
                            class="img-fluid rounded " style="width: 300px;"><br><br>
                        <h2>49.99$/an</h2>
                        <p> Magnifique poisson du massif corallien.</p>
                        <p><a class="btn btn-primary" href="#" role="button">Adopter &raquo;</a></p>                           
                    </b-col>
                    <b-col cols="12" md="4" class="text-center">
                        <img v-lazy="'img/images/600x600px/Poisson-11a.jpg'" alt="Raised circle image"
                            class="img-fluid rounded " style="width: 300px;"><br><br>
                        <h2>49.99$/an</h2>
                        <p> Magnifique poisson du massif corallien.</p>
                        <p><a class="btn btn-primary" href="#" role="button">Adopter &raquo;</a></p>                           
                    </b-col>
                    <b-col cols="12" md="4" class="text-center">
                        <img v-lazy="'img/images/600x600px/Poisson-12a.jpg'" alt="Raised circle image"
                            class="img-fluid rounded " style="width: 300px;"><br><br>
                        <h2>49.99$/an</h2>
                        <p> Magnifique poisson du massif corallien.</p>
                        <p><a class="btn btn-primary" href="#" role="button">Adopter &raquo;</a></p>                           
                    </b-col>
                    <b-col cols="12" md="4" class="text-center">
                        <img v-lazy="'img/images/600x600px/Poisson-13a.jpg'" alt="Raised circle image"
                            class="img-fluid rounded " style="width: 300px;"><br><br>
                        <h2>49.99$/an</h2>
                        <p> Magnifique poisson du massif corallien.</p>
                        <p><a class="btn btn-primary" href="#" role="button">Adopter &raquo;</a></p>                           
                    </b-col>
                    <b-col cols="12" md="4" class="text-center">
                        <img v-lazy="'img/images/600x600px/Poisson-14a.jpg'" alt="Raised circle image"
                            class="img-fluid rounded " style="width: 300px;"><br><br>
                        <h2>49.99$/an</h2>
                        <p> Magnifique poisson du massif corallien.</p>
                        <p><a class="btn btn-primary" href="#" role="button">Adopter &raquo;</a></p>                           
                    </b-col>
                    <b-col cols="12" md="4" class="text-center">
                        <img v-lazy="'img/images/600x600px/Poisson-15a.jpg'" alt="Raised circle image"
                            class="img-fluid rounded " style="width: 300px;"><br><br>
                        <h2>49.99$/an</h2>
                        <p> Magnifique poisson du massif corallien.</p>
                        <p><a class="btn btn-primary" href="#" role="button">Adopter &raquo;</a></p>                           
                    </b-col>
                    <b-col cols="12" md="4" class="text-center">
                        <img v-lazy="'img/images/600x600px/Poisson-16a.jpg'" alt="Raised circle image"
                            class="img-fluid rounded " style="width: 300px;"><br><br>
                        <h2>49.99$/an</h2>
                        <p> Magnifique poisson du massif corallien.</p>
                        <p><a class="btn btn-primary" href="#" role="button">Adopter &raquo;</a></p>                           
                    </b-col>
                    <b-col cols="12" md="4" class="text-center">
                        <img v-lazy="'img/images/600x600px/Poisson-17a.jpg'" alt="Raised circle image"
                            class="img-fluid rounded " style="width: 300px;"><br><br>
                        <h2>49.99$/an</h2>
                        <p> Magnifique poisson du massif corallien.</p>
                        <p><a class="btn btn-primary" href="#" role="button">Adopter &raquo;</a></p>                           
                    </b-col>
                    <b-col cols="12" md="4" class="text-center">
                        <img v-lazy="'img/images/600x600px/Poisson-18a.jpg'" alt="Raised circle image"
                            class="img-fluid rounded " style="width: 300px;"><br><br>
                        <h2>49.99$/an</h2>
                        <p> Magnifique poisson du massif corallien.</p>
                        <p><a class="btn btn-primary" href="#" role="button">Adopter &raquo;</a></p>                           
                    </b-col>
                    <b-col cols="12" md="4" class="text-center">
                        <img v-lazy="'img/images/600x600px/Poisson-19a.jpg'" alt="Raised circle image"
                            class="img-fluid rounded " style="width: 300px;"><br><br>
                        <h2>49.99$/an</h2>
                        <p> Magnifique poisson du massif corallien.</p>
                        <p><a class="btn btn-primary" href="#" role="button">Adopter &raquo;</a></p>                           
                    </b-col>
                    <b-col cols="12" md="4" class="text-center">
                        <img v-lazy="'img/images/600x600px/Poisson-20a.jpg'" alt="Raised circle image"
                            class="img-fluid rounded " style="width: 300px;"><br><br>
                        <h2>49.99$/an</h2>
                        <p> Magnifique poisson du massif corallien.</p>
                        <p><a class="btn btn-primary" href="#" role="button">Adopter &raquo;</a></p>                           
                    </b-col>
                    <b-col cols="12" md="4" class="text-center">
                        <img v-lazy="'img/images/600x600px/Poisson-21a.jpg'" alt="Raised circle image"
                            class="img-fluid rounded " style="width: 300px;"><br><br>
                        <h2>49.99$/an</h2>
                        <p> Magnifique poisson du massif corallien.</p>
                        <p><a class="btn btn-primary" href="#" role="button">Adopter &raquo;</a></p>                           
                    </b-col>
                    <b-col cols="12" md="4" class="text-center">
                        <img v-lazy="'img/images/600x600px/Poisson-22a.jpg'" alt="Raised circle image"
                            class="img-fluid rounded " style="width: 300px;"><br><br>
                        <h2>49.99$/an</h2>
                        <p> Magnifique poisson du massif corallien.</p>
                        <p><a class="btn btn-primary" href="#" role="button">Adopter &raquo;</a></p>                           
                    </b-col>
                    <b-col cols="12" md="4" class="text-center">
                        <img v-lazy="'img/images/600x600px/Poisson-23a.jpg'" alt="Raised circle image"
                            class="img-fluid rounded " style="width: 300px;"><br><br>
                        <h2>49.99$/an</h2>
                        <p> Magnifique poisson du massif corallien.</p>
                        <p><a class="btn btn-primary" href="#" role="button">Adopter &raquo;</a></p>                           
                    </b-col>
                    <b-col cols="12" md="4" class="text-center">
                        <img v-lazy="'img/images/600x600px/Poisson-24a.jpg'" alt="Raised circle image"
                            class="img-fluid rounded " style="width: 300px;"><br><br>
                        <h2>49.99$/an</h2>
                        <p> Magnifique poisson du massif corallien.</p>
                        <p><a class="btn btn-primary" href="#" role="button">Adopter &raquo;</a></p>                           
                    </b-col>
                    <b-col cols="12" md="4" class="text-center">
                        <img v-lazy="'img/images/600x600px/Poisson-25a.jpg'" alt="Raised circle image"
                            class="img-fluid rounded " style="width: 300px;"><br><br>
                        <h2>49.99$/an</h2>
                        <p> Magnifique poisson du massif corallien.</p>
                        <p><a class="btn btn-primary" href="#" role="button">Adopter &raquo;</a></p>                           
                    </b-col>
                    <b-col cols="12" md="4" class="text-center">
                        <img v-lazy="'img/images/600x600px/Poisson-26a.jpg'" alt="Raised circle image"
                            class="img-fluid rounded " style="width: 300px;"><br><br>
                        <h2>49.99$/an</h2>
                        <p> Magnifique poisson du massif corallien.</p>
                        <p><a class="btn btn-primary" href="#" role="button">Adopter &raquo;</a></p>                           
                    </b-col>
                    <b-col cols="12" md="4" class="text-center">
                        <img v-lazy="'img/images/600x600px/Poisson-27a.jpg'" alt="Raised circle image"
                            class="img-fluid rounded " style="width: 300px;"><br><br>
                        <h2>49.99$/an</h2>
                        <p> Magnifique poisson du massif corallien.</p>
                        <p><a class="btn btn-primary" href="#" role="button">Adopter &raquo;</a></p>                           
                    </b-col>
                    <b-col cols="12" md="4" class="text-center">
                        <img v-lazy="'img/images/600x600px/Corail-9a.jpg'" alt="Raised circle image"
                            class="img-fluid rounded " style="width: 300px;"><br><br>
                        <h2>99.99$/an</h2>
                        <p> Précieux corail du grand massif.</p>
                        <p><a class="btn btn-success" href="#" role="button">Adopter &raquo;</a></p>                           
                    </b-col>
                    <b-col cols="12" md="4" class="text-center">
                        <img v-lazy="'img/images/600x600px/Poisson-28a.jpg'" alt="Raised circle image"
                            class="img-fluid rounded " style="width: 300px;">
                        <h2>Prix réduit! 19.99$/an</h2>
                        <p> Magnifique poisson du massif corallien.</p>
                        <p><a class="btn btn-warning" href="#" role="button">Adopter &raquo;</a></p>                           
                    </b-col>
                    <b-col cols="12" md="4" class="text-center">
                        <img v-lazy="'img/images/600x600px/Corail-4a.jpg'" alt="Raised circle image"
                            class="img-fluid rounded " style="width: 300px;"><br><br>
                        <h2>99.99$/an</h2>
                        <p> Précieux corail du grand massif.</p>
                        <p><a class="btn btn-success" href="#" role="button">Adopter &raquo;</a></p>                           
                    </b-col>
                    
                    <b-container><br><hr></b-container>  
                </b-row>
            </b-container>
            <!-- Fin du Bocal -->

            <!-- Formulaire contact -->
            <b-container>
                <h1>CONTACTEZ-NOUS</h1>
                <form>
                    <div class="row">
                        <div class="col-md-9">
                            <div class="form-group">
                                <input type="email" class="form-control" id="exampleFormControlInput1" placeholder="nom@exemple.com">
                                </div>
                                </div>
                                <div class="col-md-9">
                            <div class="form-group">
                                <input type="name" class="form-control" id="exampleFormControlInput1" placeholder="Nom...">
                                </div>
                                </div>
                                <div class="col-md-9">
                            <div class="form-group">
                                <input type="name" class="form-control" id="exampleFormControlInput1" placeholder="Prénom...">
                                </div>
                                </div>
                                <div class="col-md-9">
                                <div class="form-group">
                                    <input type="text" placeholder="Votre message..." class="form-control" />
                            </div>
                        </div>
                    </div>
                    <button type="button" class="btn btn-default">Envoyer!</button>
                </form>
            </b-container>
            <!-- formulaire contact fin -->
    </section>  
</template>

<script>
import { BCarousel } from "bootstrap-vue/esm/components/carousel/carousel";
import { BCarouselSlide } from "bootstrap-vue/esm/components/carousel/carousel-slide";
import { BCard } from "bootstrap-vue/esm/components/card";
import { BContainer, BCol, BRow } from "bootstrap-vue/esm/components/layout";
import { BEmbed } from 'bootstrap-vue';


export default {
  components: {
    BCarousel,
    BCarouselSlide,
    BCard,
    BContainer,
    BCol,
    BRow,
    BEmbed
  }
};
</script>
