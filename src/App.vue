<template>
  <div class="flexible-content">
    <!--Navbar-->
    <mdb-navbar class="flexible-navbar" color="stylish" position="top" dark href="#" transparent scrolling>
        <mdb-navbar-brand href="#" target="_blank"><strong>Script Sheet</strong></mdb-navbar-brand>
        <mdb-navbar-toggler  style="max-width: 1140px">
        <mdb-navbar-nav left>
          <mdb-nav-item to="/" waves-fixed active class="active"
            >Home</mdb-nav-item
          >

        </mdb-navbar-nav>
        <mdb-navbar-nav right>
          <mdb-nav-item href="https://www.linkedin.com/in/hanifah-perdilla-onissa-42a014165/" waves-fixed
            ><mdb-icon fab class="text-black" icon="linkedin"
          /></mdb-nav-item>
          <mdb-nav-item href="https://www.instagram.com/azkaahanifah/" waves-fixed
            ><mdb-icon fab icon="instagram"
          /></mdb-nav-item>
          <mdb-nav-item
            href="https://github.com/xalamander13"
            waves-fixed
            class="border border-light rounded mr-1"
            target="_blank"
            ><mdb-icon fab icon="github" class="mr-2" />My GitHub
          </mdb-nav-item>
        </mdb-navbar-nav>
      </mdb-navbar-toggler>
    </mdb-navbar>
    <!--/.Navbar-->
    <!--ViewWrapper-->
    <view-wrapper>
      <mdb-mask class="d-flex gradient justify-content-center align-items-center">
      <mdb-container>
        <mdb-row>
          <div class="white-text text-center text-md-left col-md-6 mt-xl-5 mb-5">
            <h1 class="h1-responsive font-weight-bold">Let's Collaborate! </h1>
            <hr class="hr-light"/>
            <h6 class="mb-4">It's not important, if you still as a student in school or university. Let make some project, collab, sharing knowledge. We grow together! What are you waiting for? Send your portfolio right now!</h6>
            <mdb-btn outline="white" color="white">Learn More</mdb-btn>
          </div>
        <mdb-col md="6" xl="5" class="mb-4">
        <!-- Card -->
        <mdb-card>
          <mdb-card-body>
            <form>
              <div class="white-text">
                <p class="h3 text-center py-4"><mdb-icon icon="user"/> Register</p>
                <mdb-input label="Your name" icon="user" labelColor="white" group type="text" validate error="wrong" success="right"/>
                <mdb-input label="Your email" icon="envelope" labelColor="white" group type="email" validate error="wrong" success="right"/>
                <mdb-input label="Your password" icon="lock" labelColor="white" group type="password" validate/>
              </div>
              <div class="text-center py-4 mt-3">
                <mdb-btn color="indigo" type="submit">Sign Up</mdb-btn>
              </div>
            </form>
          </mdb-card-body>
        </mdb-card>
        <!--/.Card -->
        </mdb-col>
        </mdb-row>
      </mdb-container>
      </mdb-mask>
    </view-wrapper>
    <!--/.ViewWrapper-->
    <!--Project-->
    <mdb-container>
      <section class="text-center my-5">
        <h2 class="h1-responsive font-weight-bold my-5">Our Projects</h2>
        <p class="grey-text w-responsive mx-auto mb-5">We accept more one kind of project. So you can contribute to our project based on your skill. But remember, the first thing that you sould know, this project is dedicated for student in university. Welcome freelancer!</p>
        <mdb-row class="text-center">
          <mdb-col lg="4" md="12" class="mb-lg-0 mb-4">
            <mdb-view class="overlay rounded z-depth-1">
              <img src="https://images.pexels.com/photos/163100/circuit-circuit-board-resistor-computer-163100.jpeg?auto=compress&cs=tinysrgb&dpr=2&h=650&w=940" alt="sample photo" class="img-fluid"/>
              <a>
                <mdb-mask waves overlay="white-slight"/>
              </a>
            </mdb-view>
            <mdb-card-body class="pb-0">
            <h4 class="font-weight-bold my-3">Arduino</h4>
            <p class="grey-text">Microcontroller, Electronic, Raspberry Pi, C++ and other tools. We can build a simple project with Arduino or Raspberry Pi.</p>
            <mdb-btn color="indigo" size="sm"><mdb-icon icon="clone" class="left"/> View project</mdb-btn>
          </mdb-card-body>
          </mdb-col>
          <mdb-col lg="4" md="12" class="mb-lg-0 mb-4">
            <mdb-view class="overlay rounded z-depth-1">
              <img src="https://images.pexels.com/photos/943096/pexels-photo-943096.jpeg?auto=compress&cs=tinysrgb&dpr=2&h=650&w=940" alt="sample photo" class="img-fluid"/>
              <a>
                <mdb-mask waves overlay="white-slight"/>
              </a>
            </mdb-view>
            <mdb-card-body class="pb-0">
            <h4 class="font-weight-bold my-3">Programming</h4>
            <p class="grey-text">Javascript, Back End & Front End, RESTful API, Web Services, UI/UX Design, Software QA Engineer/Tester.</p>
            <mdb-btn color="indigo" size="sm"><mdb-icon icon="clone" class="left"/> View project</mdb-btn>
          </mdb-card-body>
          </mdb-col>
          <mdb-col lg="4" md="12" class="mb-lg-0 mb-4">
            <mdb-view class="overlay rounded z-depth-1">
              <img src="https://images.pexels.com/photos/270637/pexels-photo-270637.jpeg?auto=compress&cs=tinysrgb&dpr=2&h=650&w=940" alt="sample photo" class="img-fluid"/>
              <a>
                <mdb-mask waves overlay="white-slight"/>
              </a>
            </mdb-view>
            <mdb-card-body class="pb-0">
            <h4 class="font-weight-bold my-3">SEO & Blog</h4>
            <p class="grey-text">Content Writer, Digital Marketing, Blogger, SEO (Search Engine Optimize). It's one of the most important project.</p>
            <mdb-btn color="indigo" size="sm"><mdb-icon icon="clone" class="left"/> View project</mdb-btn>
          </mdb-card-body>
          </mdb-col>
        </mdb-row>
      </section>
    </mdb-container>
    <!--/.Project-->
    <!--Contact-->
    <div class="contact mt-5 p-5" >
    <mdb-container>
      <section class="my-5">
        <h2 class="h1-responsive font-weight-bold text-center my-5">Contact us</h2>
        <p class="text-center w-responsive mx-auto pb-5">Hey freelancer, need more information? Feel free to ask us. We try to answer your question. Please type your name, email and message below. Thankyou!</p>
        <mdb-row>
          <mdb-col md="9" class="md-0 mb-5">
            <form>
              <mdb-row>
                <mdb-col md="6">
                  <div class="md-form mb-0">
                    <mdb-input type="text" id="contact-name" label="Your name" />
                  </div>
                </mdb-col>
                <mdb-col md="6">
                  <div class="md-form mb-0">
                    <mdb-input type="text" id="contact-email" label="Your email" />
                  </div>
                </mdb-col>
              </mdb-row>
              <mdb-row>
                <mdb-col md="12">
                  <div class="md-form mb-0">
                    <mdb-textarea id="contact-message" label="Your message" />
                  </div>
                </mdb-col>
              </mdb-row>
            </form>
            <div class="text-center text-md-left">
              <mdb-btn color="primary" size="md">Send</mdb-btn>
            </div>
          </mdb-col>
          <mdb-col  md="3" class="text-center">
            <ul class="list-unstyled mb-0">
              <li>
                <mdb-icon icon="map-marker" size="2x" class="blue-text"/>
                <p>Bogor, Jawa Barat, 16961</p>
              </li>
              <li>
                <mdb-icon icon="phone" size="2x" class="blue-text mt-4"/>
                <p>+62 838 02x xxx</p>
              </li>
              <li>
                <mdb-icon icon="envelope" size="2x" class="blue-text mt-4"/>
                <p>azkaahanifah@gmail.com</p>
              </li>
            </ul>
          </mdb-col>
        </mdb-row>
      </section>
    </mdb-container>
    </div>
    <!--/.Contact-->
    <main>
      <!--Footer-->
      <ftr color="primary-color-dark" class="text-center font-small darken-2">
        <div class="pt-4">
          <mdb-btn
            outline="white"
            tag="a"
            href="#"
            target="_blank"
            >Send Portfolio <mdb-icon icon="upload" class="ml-2"
          /></mdb-btn>
          <mdb-btn
            outline="white"
            tag="a"
            href="#"
            target="_blank"
            >Join as Freelancer <mdb-icon icon="user" class="ml-2"
          /></mdb-btn>
        </div>
        <hr class="my4" />
        <div class="pb-4">
          <a href="#"><mdb-icon fab icon="twitter" class="mr-3"/></a>
          <a href="#"><mdb-icon fab icon="youtube" class="mr-3"/></a>
          <a href="#"><mdb-icon fab icon="google-plus" class="mr-3"/></a>
          <a href="#"><mdb-icon fab icon="pinterest" class="mr-3"/></a>
          <a href="#"><mdb-icon fab icon="github" class="mr-3"/></a>
          <a href="#"><mdb-icon fab icon="codepen" class="mr-3"/></a>
        </div>
        <p class="footer-copyright mb-0 py-3 text-center">
          &copy; {{ new Date().getFullYear() }} Copyright:
          <a href="#"> Xalamander13 </a>
        </p>
      </ftr>
      <!--/.Footer-->
    </main>
  </div>
</template>

<script>
  import {
    mdbNavbar,
    mdbNavbarBrand,
    mdbNavItem,
    mdbNavbarNav,
    mdbNavbarToggler,
    mdbBtn,
    mdbIcon,
    mdbFooter,
    mdbMask,
    mdbCard, 
    mdbCardBody,
    ViewWrapper
  } from "mdbvue";
  export default {
    name: 'App',
    components: {
      mdbNavbar,
      mdbNavbarBrand,
      mdbNavItem,
      mdbNavbarNav,
      mdbNavbarToggler,
      mdbBtn,
      mdbIcon,
      ftr: mdbFooter,
      mdbMask,
      mdbCard, 
      mdbCardBody,
      ViewWrapper
    }
  }
</script>

<style lang="scss">
$image-path: '~@/../mdb/mdbvue/img';
@import '~@/../mdb/mdbvue/scss/mdb-free.scss';

@import url('https://fonts.googleapis.com/css?family=Roboto:300,400,500,700&display=swap');
</style>

<style scoped>
main {
  background-color: ghostwhite;
}

.contact {
  background-color: whitesmoke;
}

.flexible-content {
  transition: padding-left 0.3s;
  padding-right: 0px;
}

.flexible-navbar {
  transition: padding-left 0.5s;
  padding-left: 270px;
}

.gradient {
  background-image: url('https://images.pexels.com/photos/1363876/pexels-photo-1363876.jpeg?auto=compress&cs=tinysrgb&dpr=2&h=650&w=940');
  background-repeat: no-repeat;
  background-size: cover;
  background-position: center center;
  height: calc(100vh - 60px);
}

.card {
  background-color: rgba(126, 123, 215, 0.2);
}

</style>