<template>
  <div class="profile-page">
    <section class="section-profile-cover section-shaped my-0">
      <div class="shape shape-dark">
        <span></span>
        <span></span>
        <span></span>
        <span></span>
        <span></span>
        <span></span>
        <span></span>
      </div>
    </section>
    <section class="section section-skew">
      <div class="container">
        <card shadow class="card-profile mt--300" no-body>
          <div class="px-4">
            <div class="row justify-content-center">
              <div class="col-lg-3 order-lg-2">
                <div class="card-profile-image">
                  <a href="#">
                    <img
                      src="../assets/image/profile.jpeg"
                      class="rounded-circle"
                    />
                  </a>
                </div>
              </div>
              <div
                class="col-lg-4 order-lg-3 text-lg-right align-self-lg-center"
              >
                <div class="card-profile-actions py-4 mt-lg-0">
                  <a href="https://www.linkedin.com/in/mkkimyyc/"
                    ><base-button type="info" size="lg" class="mr-4"
                      ><i class="fa fa-linkedin fa-2x"></i></base-button
                  ></a>
                  <a href="https://github.com/DEV-MK-KIM"
                    ><base-button type="default" size="lg" class="float-right"
                      ><i class="fa fa-github fa-2x"></i></base-button
                  ></a>
                </div>
              </div>
              <div class="col-lg-4 order-lg-1">
                <!-- <div class="card-profile-stats d-flex justify-content-center">
                  <div>
                    <span class="heading">22</span>
                    <span class="description">Friends</span>
                  </div>
                  <div>
                    <span class="heading">10</span>
                    <span class="description">Photos</span>
                  </div>
                  <div>
                    <span class="heading">89</span>
                    <span class="description">Comments</span>
                  </div>
                </div> -->
              </div>
            </div>
            <div class="text-center mt-5">
              <h3>MK Kim</h3>
              <div class="h6 font-weight-300">
                <i class="ni location_pin mr-2"></i>Calgary, Alberta
              </div>
              <div class="h6 mt-4">
                <i class="ni business_briefcase-24 mr-2"></i>Full Stack
                Developer
              </div>
              <div><i class="ni education_hat mr-2"></i>and minilmalist</div>
            </div>
            <div class="mt-5 py-5 border-top text-center">
              <div class="row justify-content-center">
                <div class="col-lg-9">
                  <p>"Learning is the best way to complete human"</p>
                  <!-- <a href="#">Show more</a> -->
                </div>
              </div>
            </div>
          </div>
        </card>
      </div>
    </section>
    <div class="container my-5">
      <div class="row row-grid align-items-center">
        <div class="col-md-6 order-lg-2 ml-lg-auto"></div>
        <div class="col-lg-12 order-lg-1">
          <div class="d-flex px-3">
            <div class="pl-4">
              <h4 class="display-3">Main Projects</h4>
            </div>
          </div>
          <card shadow class="shadow-lg--hover mt-5">
            <div class="d-flex px-3">
              <div class="pl-4">
                <h5 class="title text-success">Internal API</h5>
                <p>
                  Implemented API where clients push and receive real time data
                  through static IP.
                </p>
                <small>
                  Typescript, Express.js, Google Cloud Platform - Functions,
                  Goolgle OAuth, AWS - lambda, AWS - VPC
                </small>
              </div>
            </div>
          </card>
          <card shadow class="shadow-lg--hover mt-5">
            <div class="d-flex px-3">
              <div class="pl-4">
                <h5 class="title text-warning">Contactless Delivery App</h5>
                <p>
                  Built web-app where clients can leavn their signature on their
                  mobile phone and push survey to database
                </p>
                <small>
                  Typescript, Vue, Google Cloud Platform - Functions, Goolgle
                  OAuth, Google Firestore
                </small>
              </div>
            </div>
          </card>
          <card shadow class="shadow-lg--hover mt-5">
            <div class="d-flex px-3">
              <div class="pl-4">
                <h5 class="title text-success">Archive System</h5>
                <p>
                  Implemented archive system where all real-time data are
                  archived in timely and secunre manner
                </p>
                <small>
                  Typescript, Google Cloud Platform - Functions, Google Big
                  Query (SQL), Goolge Cloud Storage, Microsoft Azure CosmosDB
                </small>
              </div>
            </div>
          </card>
          <card shadow class="shadow-lg--hover mt-5">
            <div class="d-flex px-3">
              <div class="pl-4">
                <h5 class="title text-warning">Client Portal</h5>
                <p>
                  Made portal web-app where clients can manage their data
                  including users and orders.
                </p>
                <small>
                  Vue, Typescript, Google Firestore (NoSQL), Bulma, Material CSS
                </small>
              </div>
            </div>
          </card>
        </div>
      </div>
    </div>
    <div class="container container-lg">
      <div class="d-flex my-5">
        <div class="pl-4">
          <h4 class="display-3 ml-5">Side Projects</h4>
        </div>
      </div>
      <div class="row">
        <div class="col-md-6 mb-5 mb-md-0">
          <div class="card card-lift--hover shadow border-0">
            <a href="https://decko-home-test.web.app/">
              <img
                src="../assets/image/decko.png"
                height="370"
                class="card-img"
              />
            </a>
          </div>
          <div class="lead text-center mb-5">Decko Home</div>
        </div>
        <div class="col-md-6 mb-5 mb-lg-0">
          <div class="card card-lift--hover shadow border-0">
            <a href="https://github.com/DEV-MK-KIM/blockchain">
              <img
                src="../assets/image/blockchain.jpeg"
                height="370"
                class="card-img"
              />
            </a>
          </div>
          <div class="lead text-center mb-5">Blockchain (Backend)</div>
        </div>
      </div>
      <div class="row">
        <div class="col-md-6 mb-5 mb-md-0">
          <div class="card card-lift--hover shadow border-0">
            <a href="https://github.com/DEV-MK-KIM/m_apps">
              <img
                src="../assets/image/mealapp.jpeg"
                height="370"
                class="card-img"
              />
            </a>
          </div>
          <div class="lead text-center">Meal Recipe Mobile App</div>
        </div>
        <div class="col-md-6 mb-5 mb-md-0">
          <div class="card card-lift--hover shadow border-0">
            <a href="https://ninja-geo-747a3.web.app/">
              <img
                src="../assets/image/geoninja.png"
                height="370"
                class="card-img"
              />
            </a>
          </div>
          <div class="lead text-center">Geographic Chat App</div>
        </div>
      </div>
    </div>
  </div>
</template>
<script>
export default {
};
</script>
<style>
</style>
