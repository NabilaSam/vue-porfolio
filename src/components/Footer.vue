<template >
    <div class="footer">
        <div :text="['center', 'lg-start', 'muted']">
        <div class="
            d-flex
            border-bottom
          ">
         <br>
        </div>
        <section>
          <div class="container text-center text-md-start mt-5">
           
            <div class="mt-3 d-flex 
            border-bottom">
              <div md="3" lg="4" xl="3" class="mx-auto mb-4">
              
                <div md="4" lg="3" xl="3" class="mx-auto mb-md-0 mb-4 social-links">
                  <!-- Links -->
                  <h6 class="text-uppercase  fw-bold mb-4">Contact</h6>
                 
                            <p>
                                <a href="https://github.com/NabilaSam" target="_blank">
                                        <i class="fa fa-github me-3">
                                    
                                </i>: NabilaSam</a>
                            </p>
                            <p>
                              <a href="https://www.linkedin.com/in/nabila-samsodien-a9bb6918a/" target="_blank">
                                  <i class="fa fa-linkedin me-3">
                                  </i>: Linkedin 
                    </a>
                  </p>
                  <p>
                    <i class="fas fa-envelope me-3"></i>
                    <a href="mailto: nabilasamsodien@gmail.com" target="_blank">
                    : nabilasamsodien@gmail.com </a>
                  </p>
                  <p>
                   <i class="fa fa-phone fa-0.5x"> </i> +27 82 474 9772
                  </p>
                  
                  <button type="button" class="btn-secondary btn btn-rounded">
                        <a href="./html/contact.html"></a>Contact Form
                       </button>
                </div>
                
    <br>
                
              </div>
              <!-- Grid column -->
              <!-- Grid column -->
              <!-- Grid column -->
            </div>
            <!-- Grid row -->
          </div>
        </section>
        <!-- Section: Links  -->
        <!-- Copyright -->
        <div class="text-center p-4" style="background-color: rgba(0, 0, 0, 0.05)">
          © 2023 Copyright:
          <p class="text-reset fw-bold">Nabila Samsodien</p>
        </div>
        <!-- Copyright -->
        </div>

    </div>

</template>
<script>
export default {
    
}
</script>
<style scoped>
    .footer{
    background-color: rgb(0, 0, 0);
    color: #f2f2f2;
    justify-content: center;
    display: flex;
    align-items: center;
    }

    /* Socials */

.social-links{
    margin-top: 5%;
}

.social-links a {
    text-decoration: none;
    color: #f2f2f2;
}

   
@media screen and (max-width: 1200px) 
{
.footer { 
  padding-left: 5px !important;
  padding-right: 5px !important;
    justify-content: center;
    display: flex;
} 
 
}

   
</style>

